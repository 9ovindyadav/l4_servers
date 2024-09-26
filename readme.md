# Basic TCP and UDP servers

## Project setup
1. **Requirements**:
   - Install [Node.js](https://nodejs.org/) (v20.17.0 recommended).
2. **Clone the Project**:
   ```bash
   git clone https://github.com/9ovindyadav/l4_servers.git && cd l4_servers

## TCP Server
1. **About**
	- This is a connection-oriented server, ensuring reliable communication between the client and server.

2. **Run the TCP Server:**
	```bash
	node tcp_server.js

3. **Connect to the TCP Server:**
	- From another terminal or system, use:
	    ```bash
	    telnet localhost 8000

    - After the connection is established:
    	- Write a message in the terminal.
    	- The message will be displayed in the server terminal.
    - **Note:**  If the server crashes, the connection will be lost.

## UDP Server
1. **About**
	- This is a connection-less server, offering fast, but potentially unreliable communication.

2. **Run the UDP Server:**
	```bash
	node udp_server.js

3. **Connect to the UDP Server:**
	- From another terminal or system, use:
	    ```bash
	    echo "Hii" | nc -w1 -u localhost 8001

    - After sending a message:
    	- The message will appear in the server terminal.


## Learning Sources
- [Building TCP & UDP Servers with Node JS](https://youtu.be/1acKGwbby-E?si=baPgkDC92nnRAsSH)
