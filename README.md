# Trebuchet

Trebuchet allows for a single jar file that can assit in determining if ports are available between a client and a server.


Examples:

Server:
        java -jar Trebuchet.jar [ -S<portnum> | -C<ip:port> -p<portnum> -P<portnum>]
        
Client:
        java -jar Trebuchet.jar -Clocalhost:9080 -p1238 -P55023
        

