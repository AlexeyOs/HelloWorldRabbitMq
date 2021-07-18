# RabbitMq

Hello world with `RabbitMq`  by example from [doc](https://www.rabbitmq.com/tutorials/tutorial-one-java.html)

For run on Windows, need

`javac -cp lib/amqp-client-5.7.3.jar Send.java Recv.java` - compile classes

`java -classpath .;./lib/amqp-client-5.7.3.jar;./lib/slf4j-api-1.7.31.jar;./lib/slf4j-simple-1.7.31.jar Recv` - Run class **Recv**
`java -classpath .;./lib/amqp-client-5.7.3.jar;./lib/slf4j-api-1.7.31.jar;./lib/slf4j-simple-1.7.31.jar Send` - Run class **Send**

