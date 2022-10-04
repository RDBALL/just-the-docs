---
layout: default
title: Code 401 | Class 12
parent: Code 401 Notes
---

## Reading [Web Sockets](https://www.geeksforgeeks.org/what-is-web-socket-and-how-it-is-different-from-the-http/)

* What is a Web Socket?
  * WebSocket is bidirectional, a full-duplex protocol that is used in the same scenario of client-server communication, unlike HTTP it starts from ws:// or wss://. It is a stateful protocol, which means the connection between client and server will keep alive until it is terminated by either party (client or server). After closing the connection by either of the client and server, the connection is terminated from both ends. 
* Describe the Web Socket request/response handshake and what happens once the connection is established.
  * A request is sent from the client to the server and when the handshake is returned from the server to the client, a websocket is bridged between the client and server
* Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
  * request

## [Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)

* What does the event handler io.on() do?
  * The io.on event handler handles connection, disconnection, etc., events in it, using the socket object.
* Describe some possible proof of life or proof that the code works as expected
  * Refreshing a page where io.on() has been called should show a message when a user connects or disconnects from the websocket
* What does socket.emit() do?
  * This allows you to emit functions 

## [Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)

* What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
  * WebSocket establishes http connections while Socket.IO is the library to handle WebSocket
* When would you use Socket.IO?
  * One use case for Socket.IO is when you have the need to push a message to all connected users on a specified server
* When would you use WebSockets?
  * You could use WebSockets when establishing a chat app where you just need peer to peer chat capabilities

## [OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)

* What are a couple of key takeaways from this video?
  * This video really showcased the speed at which modern applications and computer systems can compute data and render the desired response to the user. I feel like WebSocket and Socket.IO would be contained within layer 4 transport and layer 5 session. 

## [TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)

* Translate the gist of this video to a non-technical friend
  * Imagine that you want to give someone a high-five. First you ask the other person if you can give them a high five, the person responds affirmatively and then you and the other individual high-five.  


* Bookmark and Review
  * [Socket.io Documentation](https://socket.io/docs/)
  * [Socket.io Server API](https://socket.io/docs/server-api)
  * [Socket.io Client API](https://socket.io/docs/client-api)
  * [Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)

