#### RabbitMQ Configuration Images

![image](https://user-images.githubusercontent.com/63532275/88363367-7255b300-cd9d-11ea-8434-caf5af119abf.png)
![image](https://user-images.githubusercontent.com/63532275/88363430-a9c45f80-cd9d-11ea-884e-e31f3912bd98.png)
![image](https://user-images.githubusercontent.com/63532275/88363563-193a4f00-cd9e-11ea-858e-0bbdbf81ba37.png)
![image](https://user-images.githubusercontent.com/63532275/88363578-27886b00-cd9e-11ea-9221-699e43a6c713.png)
![image](https://user-images.githubusercontent.com/63532275/88363478-cfe9ff80-cd9d-11ea-8c5c-0de0b7b5e518.png)

Deployed on PCF
![image](https://user-images.githubusercontent.com/63532275/88363660-5ef71780-cd9e-11ea-9264-009294d3a30a.png)
![image](https://user-images.githubusercontent.com/63532275/88363685-6dddca00-cd9e-11ea-866b-c4b8001bbf29.png)


##### URL
http://localhost:8080/javainuse-rabbitmq/producer?empName=emp1&empId=emp001
	
##### Lets Begin-

Since RabbitMQ is built on top of Erlang, we will first need to install Erlang. Got to the Erlang downloads page and download the erlang binary file for windows which is an executable.	

- Next run the binary file downloaded and install erlang on your machine.
- Go to RabbitMQ downloads page and download RabbitMQ installation.
- Run this exe and install RabbitMQ on your machine.
- We will now start Rabbit. The above installation should have installed the RabbitMQ command prompt. Open it.
- Go to the RabbitMQ Server Location and use the command as follows-
  rabbitmq-server start
  		
- Next we will install the RabbitMQ plugin which will give use the RabbitMQ Management Console which is accessible using the browser. OR For this use the command as follows-
- rabbitmq-plugins.bat enable rabbitmq_management  
  
	
This will trigger the message to be sent to the java queue.

##### Next go to the RabbitMQ console-

http://localhost:15672/	

http://localhost:15672/#/queues


	


