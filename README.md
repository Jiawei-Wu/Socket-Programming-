# Socket-Programming-
Programming in C under Ubuntu.  
1.client.c: It will read file and send data to the edge server using TCP connection. After calculation, it will receive the result and show on the screen.  
2.edge.c: It will receive data from client and send them to the corresponding backend server using UDP connection. After calculation, it will receive results from backend servers using UDP connection and forward results to the client using TCP connection.   
3.server_and.c: It will only get data with and operation from edge server using UDP connection. After calculation, it will send results to edge server using UDP connection.   
4.server_or.c: It will only get data wiht or operation from edge server using UDP connection. After calculation, it will send results to edge server using UDP connection.    
Do not use or distribute the code without my permission.
