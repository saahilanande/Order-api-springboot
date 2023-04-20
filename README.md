# Order-api-springboot
Build a microserviced based backend project using springboot, mysql and active MQ to Build Restful Apis to create a new order or fetch existing orders. Also built a Simple Frontend using Thymeleaf, Bootstrap and Datatable to show the execution of the APIs.

Spring boot starter library is used to create RestApis while I have also used Rest templates in the same project to consume that api i have made and present it to the Frontend of the application. As soon as the A new Order is created, in the backend SMPT protocol is used to create a email to send to the user. This email is send Asynchonously through a message broker Active MQ here. To also listen the message broker a new service is also created in the same project.
