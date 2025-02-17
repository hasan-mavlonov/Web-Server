# Socket Programming & Networking Projects

This repository contains various networking and socket programming assignments, covering fundamental concepts of client-server communication, UDP/TCP protocols, and proxy servers. These projects demonstrate practical implementations of network applications using Python.

## Projects Included

### 1. UDP Pinger
- **UDP Pinger Client** (`UDP Pinger Client.py`)
- **UDP Pinger Server** (`UDP Pinger Server.py`)
- Implements a simple UDP-based ping system to measure network latency.

### 2. Mail Client
- **Mail Client** (`Mail Client.py`)
- A simple email-sending client using sockets.

### 3. Web Proxy Server
- **Web Proxy** (`Web Proxy.py`)
- Implements a basic HTTP proxy server to handle client requests and forward them to the destination.

### 4. Web Server
- **Web Server** (`Web Server.py`)
- A simple HTTP web server that serves static files such as `index.html`.

### 5. HTML Page
- **index.html** (`index.html`)
- A sample webpage to be served by the web server.

## Requirements
- Python 3.x
- Basic knowledge of socket programming

## How to Run
Each script can be executed individually. Below are general instructions:

### Running the UDP Pinger
```sh
python3 "UDP Pinger Server.py"
python3 "UDP Pinger Client.py"
```

### Running the Web Server
```sh
python3 "Web Server.py"
```

### Running the Proxy Server
```sh
python3 "Web Proxy.py"
```

## Future Improvements
- Enhance proxy server to support HTTPS
- Implement a multi-threaded web server
- Add logging and error handling

## License
This project is for educational purposes. Feel free to use and modify it as needed.

