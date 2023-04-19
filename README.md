# TODO-LIST

*OBJECTIVE:*

To-do lists offer a way to increase productivity, stopping you from forgetting things, helps prioritise tasks, manage tasks effectively, use time wisely and improve time management as well as workflow.


*TOOLS AND TECHNOLOGIES USED:*

1. JSP - 2.2 +
2. IDE – Netbeans 8.2
3. JDK – 8
4. Apache Tomcat - 8.0.27.0
5. JSTL - 1.2.1
6. Servlet API - 2.5 
7. MySQL - mysql-connector-java-8.0.13.jar


*FUNCTIONS USED:*

1. Insert – When we add todos to the list, then we use the insert function. The added todos get stored in the Database.
2. Update – After adding todos, the task status may be in progress, but when the task gets completed, the task status updates to completed using the update function.
3. Display – When we login the Todo Web App, all the lists of Todos are displayed to the client using the display function.
4. Delete – When the Todo is unused, the specific todo can be deleted using the delete function.


*MODULES:*

User Registration Module - 
1. Create a JavaBean - User.java
2. Configure JDBC Connection- JDBCUtils.java
3. DAO Layer - UserDao.java
4. Controller Layer - UserController.java
5. View Layer - register.jsp

Login Module - 
1. Create a JavaBean - LoginBean.java
2. DAO Layer - LoginDao.java
3. Controller Layer - LoginController.java
4. View Layer - login.jsp
5. Model Layer - Todo.java
6. DAO Layer - TodoDao.java and TodoDaoImpl.java
7. Controller Layer - TodoController.java
8. View Layer - todo-form.jsp and todo-list.jsp


*HOW THE PROJECT WORKS:*

![Picture2](https://user-images.githubusercontent.com/88264132/232804680-dcd8fd74-e0f4-4aa1-b174-294cd399c65f.png)
<b><p align="center">Fig 1: User Registration Form</p></b>

<br></br>

![Picture3](https://user-images.githubusercontent.com/88264132/232825108-d87349b8-7310-49a0-ac26-6a237b5f6e0c.png)
<b><p align="center">Fig 2: Login Form</p></b>

<br></br>

![Picture4](https://user-images.githubusercontent.com/88264132/232826730-36df8b73-12fc-405b-ad44-7172ef2d8ba5.png)
<b><p align="center">Fig 3: User Table</p></b>

<br></br>

![Picture5](https://user-images.githubusercontent.com/88264132/232829356-dfec221b-89ab-43e4-a8e2-cfe0b584662d.png)
<b><p align="center">Fig 4: To-do Table</p></b>

<br></br>

![Web capture_18-4-2023_193211_](https://user-images.githubusercontent.com/88264132/232832351-be0cea12-9e71-4cbe-a730-94ef2307727e.jpeg)
<b><p align="center">Fig 5: Add Todo, Update Todo, List Todo, Delete Todo</p></b>

<br></br>

![Picture6](https://user-images.githubusercontent.com/88264132/232833480-80f484c5-1b07-476d-8a7a-6b10772dac05.png)
<b><p align="center">Fig 6: Process of Adding Todo</p></b>

<br></br>

*FUTURE IMPROVEMENTS ON THE PROJECT:*

1. Progress Bar can be implemented in each Todo.
2. Email and Contact No. option and verification can be implemented.
3. Captcha can be implemented during Registration.
4. Reminder can be implemented through notifications to complete due tasks within deadline.
5. Profile Picture Upload option can be implemented.
6. Database synchronization by mail can be well implemented.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

*PLEASE NOTE:*

This project was collaboratively prepared by:  
1) <a href="https://github.com/arnab-maitra?tab=repositories" target="_blank">Arnab Maitra</a>
2) <a href="https://youtube.com/" target="_blank">Subhadeep Puitandi</a>
3) <a href="https://youtube.com/" target="_blank">Ankita Mukherjee</a>
4) Soubhik Ghosh
5) Lekha Mehta
