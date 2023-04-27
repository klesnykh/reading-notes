# Class 19 Reading Notes

**AWS SQS vs SNS**  
1\. SNS does not persist messages, it delivers and deletes. SQS can persist messages for up to 14 days  
2\. A good one for SNS is alerts, a good one for SQS is how car sensors save data on your screen and update once in a while  

**AWS SNS and SQS**  
1\. SNS just has a bunch of subscribers, SQS doesn't use a fan out approach  
2\. client is subscribed to the sns, whenever something happens sns sends a notification to that subscriber  

**SQS and SNS Basics**  
1\. RedBus in india used it, car companies use it for their sensors and they're able to use the data for future cars
