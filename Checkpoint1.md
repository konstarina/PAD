# Real-time Taxi Application
## Checkpoint 1
### General overview of applciation objectives
Clients and servers using the HTTP Protocol establish a single connection per request. The client initiates communication and the server responds. 
After the request/response cycle finishes, the connection closes. 
For authentication method the client sends a user's credentials to the server at least once. 
The client sends the secure string back to the server in subsequent requests to validate the user's identity. 
The server stores a record that associates the user with the secure string, usually in a database table. 
When the user logs out of the application, the server deletes that record, invalidating any additional attempts to use the old string for authentication.

#### Services
* token-based authentication with JSON Web Tokens
* create and update data on the server
* handling WebSocket connection
* send messages to the UI from the server via WebSockets

### Description of the outbound API endpoints
### Description of all internal API endpoints
	
### List of technologies to be used
* Server-side will be implemented in Python, Django (web sockets, Django Channels)
* Client-side in React for authentication and authorization processes
* Docker Engine and Docker Compose
* Postgres
	
### Architecture system diagram
