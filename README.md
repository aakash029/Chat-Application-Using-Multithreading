Chat Application Using Multithreading:

This is a simple multithreaded chat application built using Java Sockets. It supports multiple clients who can chat with each other via a  server.



Features:

_ TCP-based communication
- Server handles multiple clients using threads
- Broadcasts messages from one client to all others
- Console-based interface





Requirements:

- Java JDK 8 or higher
- Terminal or command line interface



Running the application



1. Start the Server
java ChatServer    
The server will start on port 12345.

2. Start One or More Clients
In separate terminals, run:

java ChatClient  
Each client will connect to the server and can send/receive messages.

 Usage:

Type messages in the client terminal and press Enter to send.
Messages will be broadcast to all other connected clients.
Close the terminal to disconnect.  
 File Structure:

 1. ChatServer.Java.      # Server-side code 

2. ChatClient.java   # Client-side code. 

 Notes:

This is a basic example for educational purposes.


 Author:

Developed by:   
Aakash Kumar.      
Irfan Ahmad Ansari.    
Gaurav Chaudhary    
Sachin Kumar
