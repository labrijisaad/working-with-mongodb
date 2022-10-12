## `Creating documents in MongoDB with the insert method`

- Insert five documents into the collection languages
>![image](https://user-images.githubusercontent.com/74627083/195308790-2f0267f5-cec0-468e-9a4e-8a250bf1985f.png)

## `Reading documents by listing them, counting them and matching them to a query`

- Find the count of documents.
>![image](https://user-images.githubusercontent.com/74627083/195309036-c1f93867-93fa-4a6f-bf82-a35b05908581.png)

- List the first document in the collection.
>![image](https://user-images.githubusercontent.com/74627083/195309322-5eda02b8-d063-4caa-a4ee-bd504623beba.png)


- List all documents in the collection.
>![image](https://user-images.githubusercontent.com/74627083/195309494-9e1d905f-6af5-41fa-919c-792bcdecbea5.png)

- List first 3 documents in the collection.
>![image](https://user-images.githubusercontent.com/74627083/195309695-7eb86701-9281-4bbd-807f-30ced4ef1f71.png)

- Query for "python" language.
>![image](https://user-images.githubusercontent.com/74627083/195309922-49c6b9a8-8ae1-4052-b519-c41f1affe62b.png)

- Query for "object oriented" languages.
>![image](https://user-images.githubusercontent.com/74627083/195310107-9e7de931-bb15-4dbc-b859-6875308fe5f0.png)

- List only specific fields.
>>> Using a projection document WE can specify what fields we wish to see or skip in the output.

>![image](https://user-images.githubusercontent.com/74627083/195310735-36af03af-835b-4dca-9f30-e1cebdcde8c5.png)
This command lists all the documents with only name field in the output.

![image](https://user-images.githubusercontent.com/74627083/195311081-4c2d197e-c678-4378-b5ac-f6027a9b52e0.png)
This command lists all the documents without the name field in the output.


![image](https://user-images.githubusercontent.com/74627083/195311466-36661c25-8413-403f-834d-bed5d259265c.png)
This command lists all the "object oriented" languages with only "name" field in the output.

## `Updating documents in MongoDB based on specific criteria`

The **`updateMany`** command is used to update documents in a mongodb collection, and it has the following generic syntax :

      db.collection.updateMany({what documents to find},{$set:{what fields to set}})

- Adding a field description with value programming language to all the documents.
>![image](https://user-images.githubusercontent.com/74627083/195322101-ec706e76-cb93-49a1-a442-cf121041325d.png)

- Setting the creater for python language.
>![image](https://user-images.githubusercontent.com/74627083/195322347-5d9590af-3003-4055-ab9e-4cae8a2d80f1.png)

- Setting a field named **compiled** with a **value true** for all the object oriented languages.
>![image](https://user-images.githubusercontent.com/74627083/195322622-7edc298a-5676-44d3-897c-9b889ab011fb.png)

## `Deleting documents in MongoDB based on specific criteria`

- Deleting the scala language document
>![image](https://user-images.githubusercontent.com/74627083/195323044-357c60d3-5d69-45b1-b8c3-792d1168a88e.png)

- Deleting the object oriented languages
>![image](https://user-images.githubusercontent.com/74627083/195323288-7985a4b4-c038-4765-87f7-550386ff8e05.png)

- Delete all the documents in a collection.
>![image](https://user-images.githubusercontent.com/74627083/195323417-a9ce596f-80d6-4263-bc9d-26b95f568f55.png)





# `Author`
<a href="https://www.linkedin.com/in/labrijisaad/" target="_blank">Saad LABRIJI</a>


# `Change Log`
| Date (YYYY-MM-DD) | Version | Changed By    | Change Description                                 |
| ----------------- | ------- | ------------- | -------------------------------------------------- |
| 2022-10-12        | 1.0     | Labriji saad  | Added the lab                                      |



