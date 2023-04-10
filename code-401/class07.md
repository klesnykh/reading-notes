# Class 07 Reading Notes

**Intro to JWT**  
1\. A way of securely transmitting info between parties as a JSON object  
2\. Authorization or exchangign info  
3\. In the second part called the payload  

**Are JWT's Secure?**  
1\. Because you need to still know the secret  
2\. the hash, payload and secret  
3\. When the sender and receiver both know the hash and the secret then you can basically add the secret to the data you want to send, and apply the hash to it and it makes it so no one can read it other than the person that knows the hash used and the secret in order to decrypt it  

**JWTs Explained**  
1\. Because info is verified and trusted because it is digitally signed and also compact/fast  
2\. Once a user logs in that user is assigned a token, and instead of having to log in for everything that token can just be sent, making everything compact and quicker  
3\. hash, payload and secret  
