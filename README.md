# Multi-threaded-Proxy-Server

This project is a multi-threaded proxy server that allows clients to send requests to a server and receive responses. The server leverages threads to handle multiple client connections concurrently, providing efficient and scalable communication.

## Features

* Proxy server: The server listens for client connections and spawns a new thread for each incoming client, allowing simultaneous handling of multiple requests.
* Client interaction: Clients can connect to the server and send messages to request information.
* Wikipedia summary: The server retrieves a summary of a Wikipedia article based on the client's request and sends it back as a response.

## Dependencies

* Python 3.x

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   
2. No additional dependencies are required for this project.

## Usage

1. Start the server by running the 'server.py' file:
   ```bash
   python server.py
   ```
   The server will start and display the IP address and port it is listening on.
 
2. Connect the client to the server by running the 'client.py' file:
   ```bash
   python client.py
   ```
   The client will establish a connection with the server and display a message indicating the successful connection.
   
3. Enter a query or message in the client's input prompt ('>'). The server will process the request and return a summary of the corresponding Wikipedia article.

4. To disconnect from the server, enter !DISCONNECT as the message in the client. The client will terminate the connection.

5. You can run multiple instances of the client to test concurrent requests handled by the server.

## Acknowledgments

This project was developed using the socket and threading modules in Python and utilizes the Wikipedia library to retrieve article summaries.
   
