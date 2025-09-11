Assignment - 1 
Microservices Architecture

Reference - https://sjsu.instructure.com/courses/1611826/files?preview=83311694

This repository demonstrates a simple microservices architecture using Python and Flask.

It includes two independent services: <br>
	User Service – Handles user management. <br>
	Order Service – Handles order management.

The services communicate with each other via HTTP requests, showcasing how microservices interact in a distributed system.

Detailed description of setup and implementation: <br>

I started by installing the necessary dependencies (Requests and Flask) and setting up a virtual environment for this assignment.  I then made two microservices(as in two different folders in the same repository): an Order Service that runs on port 5002 and a User Service that runs on port 5001.  I was able to communicate with both services using HTTP requests after they were operational(spinned up).  For instance, I could use the User Service to create a new user and then use the Order Service to place an order, which would retrieve the user information from the User Service.  This demonstrated how the two separate services, which were created and implemented independently, interact via REST APIs.

Here are the sample output requests and responses: 

1. Create User 
![img_3.png](images/create_user.png)
2. Get User
![img.png](images/get_user.png)
3. Create Order
![img_1.png](images/create_order.png)
4. Get Order
![img_2.png](images/get_order.png)

Below are the logs from the application showing the services starting up on their respective ports and successfully handling incoming requests.<br>

User (5001) <br>

![img_4.png](images/user_service_logs.png)

Order(5002) <br>

![img_6.png](images/order_Service_logs.png) <br>

