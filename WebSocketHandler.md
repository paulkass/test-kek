# WebSocketHandler Class

* Params
  * Logger
* Constructor
  * (1)
  * (2)
* handles connection of a new socket
  * (3)
  * (4)
  * (5)
  * (6)
  * (7)
  
  1. Assign params to be the arguments passed in
  2. Add handler for time expiration of strings.
  3. Check that the request came in to the right handler. If not, log and reject the connection.
  4. Create a new WAMP handler to deal with incoming connection.
  5. Add handler for closing of socket.
  6. Add handler for exceptions in socket.
  7. Delegate the socket connection to the WAMP handler.
