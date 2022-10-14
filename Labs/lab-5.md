## `Access the MongoDB database from Python with the pymongo driver`

- Install the pymongo driver
>![image](https://user-images.githubusercontent.com/74627083/195726067-00d44ba0-516f-4838-ad03-8507a899392c.png)
This installs the Python mongodb driver as shown in the image

- Starting the server
>![image](https://user-images.githubusercontent.com/74627083/195800888-77e2c54e-30e2-470b-b7e2-f4ee87c2949f.png)
>![image](https://user-images.githubusercontent.com/74627083/195801063-c2b57760-5a81-4598-b49a-3edfc10af3c2.png)
Note down the **user name*** and ***password**, that are be displayed in the last line of the output of the **start_mongo** command.

- Connecting to mongodb server using Python
    -  Creating a new file `mongo_connect.py`
    >![image](https://user-images.githubusercontent.com/74627083/195801564-216fb220-f671-4ff6-a3ca-a416738a5107.png)
    -  Copy and paste the below code into the newly opened file.
```py

from pymongo import MongoClient
user = 'root'
password = 'MjYwMzUtc21hc2hn' # CHANGE THIS WITH YOUR OWN PASSWORD 
host='localhost'
#create the connection url
connecturl = "mongodb://{}:{}@{}:27017/?authSource=admin".format(user,password,host)


# connect to mongodb server
print("Connecting to mongodb server")
connection = MongoClient(connecturl)


# get database list
print("Getting list of databases")
dbs = connection.list_database_names()

# print the database names

for db in dbs:
    print(db)
print("Closing the connection to the mongodb server")


# close the server connecton
connection.close()
```




## `Perform basic operations such as selecting, inserting and listing using Python`
## `Create a Python program to run the MongoDB operations`










# `Author`
<a href="https://www.linkedin.com/in/labrijisaad/" target="_blank">Saad LABRIJI</a>


# `Change Log`
| Date (YYYY-MM-DD) | Version | Changed By    | Change Description                                 |
| ----------------- | ------- | ------------- | -------------------------------------------------- |
| 2022-10-12        | 1.0     | Labriji saad  | Added the lab                                      |



