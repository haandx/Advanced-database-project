# Advanced-database-project 
## Scenario:
A database for the management of the blood bank system focusing on the management of the staff to record the data of donors and patients The managers dealt with the requests of patients and hospitals by giving orders according to blood samples 
By using this system searching the available blood becomes easy and saves lot of time than the manual system. It will hoard, operate, recover and analyze information concerned with the administrative and inventory management within a blood bank. This system is developed in a manner that it is manageable, time effective, cost effective, flexible and much man power is not required

## DB planning:
The administration exercises that permit the phases of the information base framework advancement lifecycle to be acknowledged as proficiently and viably as could be expected under the circumstances. A significant initial phase in information base arranging is to characterize the statement of purpose for the information base framework.
### The mission statement:
characterizes the significant points of the information base framework.
### Mission objective:
ought to distinguish a specific undertaking that the information base framework must help.

## System Definition :
Describes scope and boundaries of database system and the major user views.
### 1-Scope and Boundaries:
<img src= "https://github.com/haandx/Advanced-database-project/assets/142608001/906bbfb2-04ca-4078-8911-13ddee22a8a5" width = "500">
## 2- Major User Views:
<img src= "https://github.com/haandx/Advanced-database-project/assets/142608001/dc48cd61-1972-4f78-897c-fe928688a55c" width = "500">
## 3- Cross-Reference of User Views:
<img src= "https://github.com/haandx/Advanced-database-project/assets/142608001/fc791bd0-1480-41b7-9710-d40a5455ab48" width = "500">
## 4-Requirement collection and analysis:
We have used the technique of open-ended questionnaires
<img src= "https://github.com/haandx/Advanced-database-project/assets/142608001/ec5b0538-446c-43b0-8020-f09600433251" width = "500">
## 4-Requirement collection and analysis:
We have used the technique of open-ended questionnaires
<img src= "https://github.com/haandx/Advanced-database-project/assets/142608001/ec5b0538-446c-43b0-8020-f09600433251" width = "500">
## ER MODEL:
<img src= "https://github.com/haandx/Advanced-database-project/assets/142608001/62995158-1998-4fab-a5e8-59faa419ac8f" width = "500">

## ER MAPPING SCHEMAS:
<img src= "https://github.com/haandx/Advanced-database-project/assets/142608001/8c0c2483-5617-4a27-a1bd-5ce26022eeec" width = "500">

## RELATIONSHIP BETWEEN ENTITIES:
1. Staff and Donor:
-Relationship = “registers” Type of relation = 1 to many Explanation = One recording staff can register many donors. One donor will register with one recording officer. The relationship with Recording staff and Donor is 1 to many. That’s why primary key of Recording staff is used as a foreign key in Donor.
2. Staff and patients:
-Relationship = “record” Type of relation = 1 to many Explanation = One recording staff can record many patients. One patient will be recorded by one recording staff. The relationship with staff and patients is 1 to many. That’s why primary key of staff is used as a foreign key in patients.
3. patients and Manager:
-Relationship =“requests in ” Type of relation = 1 to many Explanation = One patients can request blood to one manager and one manager can handle requests from many patients. The relationship with Blood Bank Manager and patients is 1 to many. That’s why primary key of Blood Manager is used as a foreign key in patients
4. Hospital and Manager:
-Relationship = “gives order ” Type of relation = 1 to many Explanation = One Blood bank manager can handle and process requests from many hospitals. One hospital will place request to on blood bank manager The relationship with Blood Bank Manager and Hospital info is 1 to many. That’s why primary key of Blood Bank manager is used as a foreign key in Hospital info.
5. Manager and Blood Specimen:
-Relationship = “deales with ” Type of relation = 1 to many Explanation = One Blood bank manager can manage many blood specimen and one specimen will be managed by one manager. The relationship with Blood Bank manager and Blood Specimen is 1 to many. That’s why primary key of Blood Bank manager is used as a foreign key in Blood Specimen
## Logical database Design: 
<img src= "https://github.com/haandx/Advanced-database-project/assets/142608001/293af381-9f8b-4b96-bbd1-3a2ba8cb0eb4" width = "500">
## Physical database Design: 
<img src= "https://github.com/haandx/Advanced-database-project/assets/142608001/59631b6a-9c04-4f47-9482-cd22c428c251" width = "500">
## DBMS selection:
### 1- Determine and study requirements:
<img src= "https://github.com/haandx/Advanced-database-project/assets/142608001/77fcbddc-d5dd-4f2a-b45d-35d92679788b" width = "500">
### 2- shortlist two or three products:
- MySQL
- MongoDB 
- Amazon Simple Storage Service (S3)
- Elasticsearch
### 3-evaluate products: 
1. MySQL 
2. MongoDB 
3. Amazon Simple Storage Service (S3) 
4. Elasticsearch
5- recommend selection and produce report


