# final-project-alex-and-megan
final-project-alex-and-megan created by GitHub Classroom
Purpose: to create/ design a normalized database and data warehouse that has domain, entity, and relational integrity. 

CourseDataERD.pdf- ERD                                  
1.  Created ERD to demonstrate organization of relational database. Database contains three tables: course meetings, courses, course catalog

CourseDataDictionary.md- Data Dictionary                        
2.	Created file that defines every column of our database 

CourseDataETL.ipynb- Relational Database      
3.	ETL Source Data using SQLite3 tool for Fall 2014-2018, Spring 2015-2019, Spring Break 2017, Summer 2015-2018, and winter 2015-2018.                                   
4.  Created tables: coursemeetings, courses, coursecatalog                                
5.	Populated each respective table with the imported data from each term                         

CourseDataTests.ipynb- Test Database Integrity                                  
6.	Tested domain integrity of CourseData.db                      
7.	Tested entity integrity of CourseData.db                        
      a. SELECT COUNT (*) should be the same as SELECT DISTINCT COUNT (*)                                             
8.	Tested relational integrity of CourseData.db
      a. Created JOIN statements to see if they run. 

CourseDataWarehouse.db- Design/Build Data Warehouse                                     
9.	Created ERD using the star schema design                                      
10.	Created data warehouse                                      

CourseDataWarehouseDemo.ipynd- Test Data Warehouse                          
11.	Wrote queries to show how useful the data warehouse is
