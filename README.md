# Key-Value-Data-Store
File based Data Store to perform Create,Read and Delete key-Value Data in File

This File Contains 2 .jar file
     
	1. FileDB.jar
	
     2.json-simple-1.1.jar
 
 
These Both file need to add in your project in order to use the functionality.

This jar files allow you to CREATE,READ and DELETE the data in the file.

To use all the functionality of this project you can call any the Function by creating "Object" of class "DataStore".

Eg:
     DataStore Obj = new DataStore;
     
     
Function Supported:


createFile()

createFile("Specific Path")


addData("Your-key",#Integer-Value)

addData("Your-key",#Integer-Value,#Timeout-session-in-seconds)


readData("Your-Key")


deleteData("Your-Key")


Eg.: 

     obj.createFile();

     obj.addData("Shubham",9868);
