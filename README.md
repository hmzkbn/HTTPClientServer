# HTTPClientServer


Web Client:
- The client reads the URL of the web page or image to be fetched from the server from the command line (using, for instance, System.in).
- The client opens a connection (stream socket) to the web-server.
- The client sends an HTTP request to the server according to the HTTP standard.
- The server responds with an HTTP reply.
- The client reads and interprets the response and stores the file on its local hard disk.

Web Server:
- This server is only  to implement the HTTP method for retrieving web pages from the server (not for posting data to the server, etc.). 
- If the server receives such a request, it fetches the requested file from its local hard disk and sends it back
to the client using a suitable HTTP response. 
- If the file does not exist, the server should respond with a suitable HTTP error message. 
- For all other requests, the server should respond with the error “(functionality) not Implemented” according to the HTTP protocol.
- Implementation of the HTTP interaction using socket programming and by implementing the necessary subset of the HTTP protocol (without using high-level classes implementing the HTTP interaction).
