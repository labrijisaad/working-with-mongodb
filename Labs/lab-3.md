## `Measure the time it takes to execute a query with the explain function`

- Insert documents
Let us insert a lot of documents into the newly created collection.

      use training
      for (i=1;i<=200000;i++){
          print(i);
          db.bigdata.insert(
          {"account_no":i,"balance":Math.round(Math.random()*1000000)}
         )
       }

  - The code given below will insert 200000 documents into the `bigdata` collection. ( `bigdata` collection was already created )
  - Each document would have a field named `account_no` which is a simple auto increment number.
  - And a field named `balance` which is a randomly generated number, to simulate the bank balance for the account.
>![image](https://user-images.githubusercontent.com/74627083/195717375-788ffd23-27c8-459d-ae70-50cd6e19778b.png)

- Verifying that 200000 documents 
>![image](https://user-images.githubusercontent.com/74627083/195717772-ee32aa14-37df-49a6-9f34-e74f59b9abee.png)

- Measure the time taken by a query
Let us run a query and find out how much time it takes to complete.

      db.bigdata.find({"account_no":58982}).explain("executionStats").executionStats.executionTimeMillis
    
  - Let us query for the details of account number `58982`
  - We will make use of the explain function to find the time taken to run the query in milliseconds.
> ![image](https://user-images.githubusercontent.com/74627083/195718294-495cf224-9db5-4b8d-bb29-4c1e662603d4.png)
Number of milliseconds it took to run the query

## `Describe the process of creating, listing and deleting indexes`

- Working with indexes
  - Creating an index on the field `account_no`
>![image](https://user-images.githubusercontent.com/74627083/195718647-0c79cb71-a6ce-4421-8ffe-610f0a2db02d.png)

- Listing of indexes on the bigdata collection
>![image](https://user-images.githubusercontent.com/74627083/195718964-072ec8d6-3553-466f-9e9a-027071bf5785.png)

## `Evaluate the effectiveness of an index`

- Find out how effective an index is

      db.bigdata.find({"account_no": 69271}).explain("executionStats").executionStats.executionTimeMillis

  - Let us run a query and find out how much time it takes to complete, using an index.
  - Let us query for the details of account number `69271`
>![image](https://user-images.githubusercontent.com/74627083/195719478-1d6d1439-bd83-45da-9694-7b3a71eb014e.png)
Number of milliseconds it took to run the query

- Delete an index ( deleting the index we created earlier )
>![image](https://user-images.githubusercontent.com/74627083/195720051-8fd8e448-03dc-466e-a4a0-a3c2341e679c.png)

# `Author`
<a href="https://www.linkedin.com/in/labrijisaad/" target="_blank">Saad LABRIJI</a>

# `Change Log`
| Date (YYYY-MM-DD) | Version | Changed By    | Change Description                                 |
| ----------------- | ------- | ------------- | -------------------------------------------------- |
| 2022-10-13        | 1.0     | Labriji saad  | Added the lab                                      |
