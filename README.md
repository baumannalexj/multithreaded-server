# multithreaded-server
Uses Java socket lib to create a multi threaded server.

Takes input form users, and serves jokes or proverbs based on a flag set by an admin at runtime.

Also manages user session to prevent serving the same joke/proverb until list is exhausted.

Requires >= Java 1.8

To run:

`mvn compile`

`java Main.java`
