# Desktop Chat Application

A chat application capable of exchanging text chat between two or multiple computers over the network using Java socket programming and JavaFX.

## Requirements ##

* Java
* Computer running macOS or Windows

## Running the Project ##

1. A server is required to relay messages between clients, therefore `ChatServer.java` needs to be executed first.
2. Once `ChatServer.java` is running, `ChatClient.java` can be executed.
3. From here on, in order for a user to send messages they need to register a username which will be cross-referenced with a list of existing
   usernames on the server to see if it is taken or not. After which they may proceed to join the server as a new user and participate in the
   chatroom.

## Future Contributions ##

There are not any security measures in place therefore putting users at risk. Registration verification, encrypting messages, or 
implementing a self-delete timer for the messages are all possible measures that can be implemented to secure the application.
