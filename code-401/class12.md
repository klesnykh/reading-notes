# Class 12 Reading Notes

**Web Sockets**  
1\. a computer communications protocol that in simple terms allows for continuous communication between a client and server, hence the name socket, like once its plugged it then its connected and thats the fastest way to send/recieve info  
2\. It starts with an HTTP request to change to a Websocket connection, once the server agrees (handshake) the connection is established and communication switches to a bidirectional binary protocol, which is faster that the http protocol  
3\. request  

**Socket.io Tutorial**  
1\. handles connection, disconnection  
2\. a proof of life could be a console.log saying a user connected  
3\. send a message to all connected clients  

**Socket.io vs Web Sockets**  
1\. Websocket is a protocol, socket.io is the library to work with it  
2\. bidirectional communication that is a little bit complex like a chat app
3\. Anything that needs constant 2 way communication but a bit more flexibility, but both of them can be used for developing real time functionality  

**OSI Model**  
1\. There are 7 layers of the OSI: Application layer, presentation, session, network, data link, and physical. They allow different operating systems to talk to each other and fully function with each other  

**TCP Handshakes Explaines**  
1\. client sends a syn segment which basically asks for a connection, server responds with a syn-ack which basically means the server responds with yes, but as long as you acknowledge one more time that you want to connect, and then the client responds with a ack, which is basically the acknowledgement that yes he does want to connect  
