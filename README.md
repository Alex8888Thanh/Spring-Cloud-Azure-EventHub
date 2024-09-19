# Spring Cloud Azure EventHub Binder
## Introduction
Connect to Azure China EventHub via connection string.  
MessageController receive the post messages and send it to EventHub.  
MessageListener consume the messages in EventHub.

## Dependencies
spring-boot 2.2.5.RELEASE  
spring-cloud-azure-eventhubs-stream-binder 1.2.2  

spring-cloud-starter-sleuth 2.2.2-RELEASE  
Note: When add sleuth dependency，will get java.lang.ClassCastException 

`
Caused by: java.lang.ClassCastException: java.lang.String cannot be cast to java.util.Map
`
