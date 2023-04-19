# Class 13 Reading Notes

**Socket.io Chat Example**  
1\. It makes a real time 2 way communication road  
2\. console.log('a user connected');  
3\. .broadcast.emit  

**Rooms**  
1\. A room is a channel that sockets can join and leave. It's useful when you have a buttload of sockets/clients and they need to communicate with only their kind  
2\. name the room 'event' in the server and emit the same 'event' with a payload in the socket, server takes care of the joining with socket.join  
3\. the same way but with a differently named event which the server handles with socket.leave  

**Namespaces**  
1\. also a communication channel. Essentially its like the parent file to the rooms/handlers/middlewares specified to that channel. It just allows for split logic/cleaner code  
2\. event handlers, rooms, middlewares  
3\. our lab 12 uses a /caps namespace for deliveries to customers. You can use a different namespace potentially for ordering ingredients for the cakes in the vendors store  
