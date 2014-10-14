TextMessaging

======================

This is an exercise in setting up the Raspberry Pi as a server and acting of clients pushing information to it.

1. First step was to setup the application with javascript. Index.js was created with an arbitary port that the http server could listen on.

2. Next an HTML webpage was served to act as the UI. The Node.js express framework was used for this.

3. Then Socket.IO was integrated into the mix. As stated in http://socket.io/get-started/chat/, Socket.IO is composed of the following:

- A server that integrates the Node.JS http server
- A client library that loads o the browser side

4. Setup so that each socket fires a unique event.

5. Setup so that each user gets it as a chat message event

======================

Next steps as suggested by http://socket.io/get-started/chat/:

- Broadcast a message to connected users when someone connects or disconnects
- Add support for nicknames
- Don’t send the same message to the user that sent it himself. Instead, append the message directly as soon as he presses enter.
- Add “{user} is typing” functionality
- Show who’s online
- Add private messaging