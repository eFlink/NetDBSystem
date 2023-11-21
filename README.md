# NetDBSystem
 This project involves developing a multithreaded, networked database server (dbserver) and a client (dbclient) in C, using HTTP-based communication for managing key/value pairs with advanced features like authentication and connection limiting.

Again, I learnt so much about C and what happens under the hood of operations I used previously in other languages without even realising it, though mine is a very simplified version. The large scope and complexity of this assignment taught me how to break down what I was doing and to sometimes gain a deeper understanding of some concepts before writting code. This was definitely one of my favourite projects I've undertaken, this course gave me a deep appreciation of lower level programming.

#### Grade Achieved: 90%

## UQ CSSE2310/CSSE7231 Assignment 4 - Networked Database Server and Client (Version 1.2 - 26 May 2022)

### Key Components:

dbserver: A networked database server handling requests to store, retrieve, and delete string-based key/value pairs via HTTP requests using a simple RESTful API.

dbclient: A simple network client capable of querying the database managed by dbserver.

### Advanced Features and Challenges:
- Multithreading: The server is capable of handling multiple client requests concurrently, showcasing an understanding of threading in C.
- RESTful API: Utilizes HTTP requests and responses for communication, adhering to REST principles for network operations.
- Authentication and Security: Implements authentication for private database access, ensuring secure transactions.
- Connection Limiting: Manages server load by limiting the number of simultaneous client connections.
- Signal Handling: Incorporates advanced signal handling for robust server operation.
- Statistics Reporting: The server is equipped with a feature to report various operational statistics upon receiving specific signals (e.g., SIGHUP).
