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

	Next go to the RabbitMQ console-http://localhost:15672/	
	
	http://localhost:15672/#/queues
	
	


