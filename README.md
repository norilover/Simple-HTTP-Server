# Simple HTTP Server

HTTP Server implemented in Java.  Processes 'GET' requests from client (e.g. a web browser), and serves the corresponding webpage if the requested file is present in the current directory.  Server runs on localhost:6880.  Optimized for Chrome and Firefox browsers.

# Usage Example

Compile Java file by changing into the relevant directory and entering the following command in your Terminal:
```
$ javac WebServer.java
```

Once compiled, run the server using:
```
$ java WebServer
```

To access index.html once the server starts running, enter the following in your browser:
localhost:6880/index.html
