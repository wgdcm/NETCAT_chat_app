## Python NETCAT
Both programs transfer messages that enter their playback terminal to the remote application at the same time without any specific sequence.

### Server.py :
Server.py listening on a defined port.

### Client.py :
Connecting Client.py to the listening port on Server.py.

### Requirements 
-Linux Operating System.

-Install Python3.

    sudo apt-get update
    sudo apt-get install python3.6

### How To Run?

Run these two python programs on the same network in separate Linux environments.
```
sudo python3 server.py
```
```
sudo python3 client.py
```

You will see a message like this on the server side.<br>
'***Use this port number '2312' to connect.***'

Use the showing port number to connect from client to server.

### Note
*Port number change for every single session.<br>
*Follow the instructions to exit the program.
   1. Press 'Ctrl+C' on both client and server-side
   2. Press 'Enter' on both client and server-side
   3. Press 'Ctrl+Z' to exit
