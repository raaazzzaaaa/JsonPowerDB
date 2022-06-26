# JsonPowerDB

This project is all about basics of JsonPowerDB (JPDB) and how to use JPDB for CRUD operations

About JsonPowerDB:

JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

Benefits of using JsonPowerDB

Simplest way to retrieve data in a JSON format.
Schema-free, Simple to use, Nimble and In-Memory database.
It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
It is low level (raw) form of data and is also human readable.
It helps developers in faster coding, in-turn reduces development cost.

Some Features of JsonPowerDB

Nimble, Simple to use, In Memory, Real-Time
Schema free - easy to maintain
Serverless Support - fast development - cuts time to market
Multi-Mode database - one solution to variety of data
Build around worlds fastest* indexing engine PowerIndex
Webservices API - low development cost
A single instance - Million Indexes
Inbuilt support to Querying Multiple Databases
Multiple security layers
Server Side Native NoSQL - best performance


Competitive Landscape
![image](https://user-images.githubusercontent.com/107788182/175831765-b1865015-066b-44a7-9878-6fd244300a6e.png)

DEMO
Update Single Record
Some important points to keep in mind
Http Method : POST
Base URL : http://api.login2explore.com:5577
End-point URL : /api/iml
Syntax:
{
 	"token": <"connection-token">,
 	"cmd": "UPDATE",
 	"dbName": <"database-name">,
 	"rel": <"relation-name">,
 	"jsonStr": {
 		<"recordNo">: {
 			<"ColumnName": "NewJsonValue">|<"New-ColumnName": "New-Column-Value">
 		}
 	}
 }
 
 Code Sample:
 
{
    "token": "90939350|-31949287484890435|90939562",
    "cmd": "UPDATE",
    "dbName": "Employee",
    "rel": "Emp-Rel",
    "jsonStr":{
      "4":{"mobile no" : "9876451273"}
    }
}
