# hotelManagement
URL Format:  http://localhost:8089/hotel/addRoom


>>used JDBC Template for queries and provisioning
>>Id is not Auto increment right now
>>need to crate a table based on Room.java Model class

Room.java
id, name, description, avaiblity

>>Room.java is an entity class with serializable support
>>ActionController.java is an controller class where all request land
>>for the start application you need to run it as spring boot
1.open WebProjectApplication.java
2.right click and select *Run As* option
3.select spring boot application and run

>>AgentService has defined all the methods for usecase
>>DAO class will be handle all database related operation
>>you can find and understand JDBC Template raw mapper for creating anothe table
