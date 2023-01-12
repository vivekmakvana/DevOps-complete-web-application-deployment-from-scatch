# DevOps-complete-web-application-deployment-from-scatch
#Backend server Details:

[Unit]\
#JDBC Configutation for Database Connection\
jdbc.driverClassName=com.mysql.jdbc.Driver\
jdbc.url=jdbc:mysql://db01:3306/accounts?useUnicode=true&characterEncoding=UTF-8&zeroDateTimeBehavior=convertToNull\
jdbc.username=admin\
jdbc.password=admin123\

#Memcached Configuration For Active and StandBy Host\
#For Active Host\
memcached.active.host=mc01\
memcached.active.port=11211\
#For StandBy Host\
memcached.standBy.host=127.0.0.2\
memcached.standBy.port=11211\

#RabbitMq Configuration\
rabbitmq.address=rmq01\
rabbitmq.port=5672\
rabbitmq.username=test\
rabbitmq.password=test\

#Elasticesearch Configuration\
elasticsearch.host =192.168.1.85\
elasticsearch.port =9300\
elasticsearch.cluster=vprofile\
elasticsearch.node=vprofilenode\
