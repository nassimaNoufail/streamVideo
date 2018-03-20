# streamVideo
stream a video using Kafka
To run this project, you should have : Zookeper,kafka, python and opencv installed, then change the "0.0.0.0" on the consumer file, 
to your local adresse, and do the same thing in server.propertites file wchich is in "C:\kafka_2.11-0.10.0.1\config", then make sure 
to run zookeper first, then kafka server and and then run :
>python producer.py
>python consumer.py
finally your project should be running in http://YourLocalAdress:5000/
