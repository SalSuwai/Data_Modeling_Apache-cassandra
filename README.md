# Data_Modeling_Apache-cassandra
Applying data modeling with Apache Cassandra and build an ETL pipeline using Python. Additionally, modeling the data by creating tables in Apache Cassandra to run queries. 




## Project summary: 

Applying data modeling with Apache Cassandra and building an ETL pipeline using Python.
Additionally, modeling the data by creating tables in Apache Cassandra to run queries. 


# Data Modeling with Apache Cassandra
For this project, we'll be working with one dataset: event_data.
We will process the data set to create a denormalized dataset table. during the modeling process we will put the queries we want to run on our minds, to make the new dataset ready to get

query the needed information. We will create tables using Apache cassandra then we will load the data into the new created tables. after loading the data in the created tables we will run our queries to test.

## Project Dataset
The data set is provided from Udacity, It has 11 columns

- artist : Artist name  [object]
- firstName: First name of user [object]
- gender: Gender of user (male or female) [object]
- itemInSession: Item number in session [int64]
- lastName: Last name of user [object]
- length: Length of the song [float64]
- level: Level (paid or free song) [object]
- location: Location of the user [object]
- sessionId: The unique ID of the session [int64] 
- song: Song title [object]
- userId: User unique ID [int64]

(The data type is from the function panda.dtypes() . Pandas actually stores pointers to strings in data frames and series, which is why object
 instead of str appears as the datatype. Understanding this is not essential - just know that strings will appear as objects in Pandas.).



There are no complicated project steps in this project. just run Project_1B_ Project_Template.ipynb 

if there's some issue with the first cells that means Udacity has changed their cursor and session configurations. but don't worry the code is carefully commented and the logic still works fine.

Have fun learning! 

## END OF PROJECT
