Assignment - 1 
Microservices Architecture

Reference - https://sjsu.instructure.com/courses/1611826/files?preview=83311694

This repository demonstrates a simple microservices architecture using Python and Flask.

It includes two independent services: <br>
	User Service – Handles user management. <br>
	Order Service – Handles order management.

The services communicate with each other via HTTP requests, showcasing how microservices interact in a distributed system.

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

![img_6.png](images/order_Service_logs.png)