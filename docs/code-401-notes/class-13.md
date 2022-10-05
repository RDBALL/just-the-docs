---
layout: default
title: Code 401 | Class 13
parent: Code 401 Notes
---

## Readings: Message Queues

* [Socket.io Chat Example](https://socket.io/get-started/chat/)

* Explain to a non-technical recruiter what the Chat Example (above) does.
  * The chat application uses socket.io to bring multiple users into a shared handshake that connects them with an intermediate server.
* What proof of life are we getting on the backend from the above app?
  * The server will log events as they are initiated by any connected client
* Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?
  * You would use the broadcast flag
* [Rooms](https://socket.io/docs/v4/rooms)

* What is a room and how might a room be useful?
  * A room is a specified subset of the Namespace that will allow users to be grouped into certain rooms. This will allow a broadcast to be sent to any specific room rather than all connected rooms.
* How do you join a room?

```JS
io.on("connection", (socket) => {
  socket.join("some room");
});
how do you leave a room?
io.on("connection", socket => {
  socket.on("disconnecting", () => {
    console.log(socket.rooms); // the Set contains at least the socket ID
  });


  socket.on("disconnect", () => {
    // socket.rooms.size === 0
  });
});
```

* [Namespaces](https://socket.io/docs/v4/namespaces/)

* What is a Namespace and what does it allow you to do?
  * A Namespace is a communication channel that allows you to split the logic of your application over a single shared connection (also called "multiplexing").
* Each namespace potentially has its own what? (hint: 3 things)
  * Event Handlers
  * Rooms
  * Middleware
* Discuss a possible use case for separate namespaces
  * Separate namespaces could be beneficial if you are trying to implement multiple features on an application. For example, In a parciel delivery server a vendor may want to be able to connect to a distributor and knows that the distributor holds a specific namespace on their socket. The vendor can then join the distributor namespace and be able to interact with them directly.
  
### Bookmark and Review

* [Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)
