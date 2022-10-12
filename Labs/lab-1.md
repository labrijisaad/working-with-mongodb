## `Getting Started with MongoDB`

- start the mongodb server. 
>![image](https://user-images.githubusercontent.com/74627083/195077524-17e3ead5-27e1-4559-b68e-a3231df16d7a.png)
The command contains the **username** and **password** to connect to mongodb server (the text after the -p option is the password). 

## `Accessing the MongoDB server using the command-line interface`

- Connect to mongodb server
>![image](https://user-images.githubusercontent.com/74627083/195078085-7caf3498-53c1-4524-ac24-29ac1ad3a2e8.png)

> Find the version of the server
![image](https://user-images.githubusercontent.com/74627083/195083200-02f635a0-0028-494e-9e48-a0d377e001b7.png)
This will show the version of the mongodb server.

## `Describing the process of listing and creating collections, which contain documents, and databases`

- List databases
>![image](https://user-images.githubusercontent.com/74627083/195083410-c053874a-1ff5-49c9-9b2b-06b17c8094df.png)
This will print a list of the databases present on the server.

- Create database
>![image](https://user-images.githubusercontent.com/74627083/195083585-5c6ffba8-dae7-484e-a820-1043f26292d5.png)
This will create a new database named training. If a database named training already exists, it will start using it.

- Create collecton
>![image](https://user-images.githubusercontent.com/74627083/195083817-9c2266ca-c366-4bf5-b73c-4eb130c224fd.png)
This will create a collection name mycollection inside the training database.

- List collections
> ![image](https://user-images.githubusercontent.com/74627083/195084876-da1efa5a-68e8-44c9-a09b-649337c63e99.png)
This will print the list of collections in your current database.

## `Performing basic operations on collections such as inserting, counting and listing documents`

- Insert documents into a collection
>![image](https://user-images.githubusercontent.com/74627083/195208549-05ab5bf1-335c-4bbf-8d21-5781f33fa2d2.png)
The above command inserts the json document `{"color":"white","example":"milk"}` into the collection.

- Inserting more documents 
>![image](https://user-images.githubusercontent.com/74627083/195209362-8451724d-ffe8-4004-832f-8fbd98de6e8a.png)
Inserting more documents...

- Count the number of documents in a collection
>![image](https://user-images.githubusercontent.com/74627083/195209524-fb2fdb61-5c93-4f8f-b075-f9c94c8e4f4a.png)
This command gives you the number of documents in the collection.

- List all documents in a collection
> ![image](https://user-images.githubusercontent.com/74627083/195209656-f69d47f7-f3ee-4fcb-827f-01ab8e6e6a14.png)
This command lists all the documents in the collection mycollection

- Disconnect from mongodb server
>![image](https://user-images.githubusercontent.com/74627083/195209772-d17e5511-73cb-4e0c-85d2-e7cfd2b6bad6.png)




# `Author`
<a href="https://www.linkedin.com/in/labrijisaad/" target="_blank">Saad LABRIJI</a>


# `Change Log`
| Date (YYYY-MM-DD) | Version | Changed By    | Change Description                                 |
| ----------------- | ------- | ------------- | -------------------------------------------------- |
| 2022-10-11        | 1.0     | Labriji saad  | Added the lab                                      |




