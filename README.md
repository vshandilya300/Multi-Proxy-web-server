Multi Proxy Web Server
Overview
The Multi Proxy Web Server is a lightweight, high-performance proxy server implemented in C. It supports routing client requests to multiple backend servers, balancing the load efficiently while handling concurrent connections. This project is ideal for low-level networking tasks and for understanding how proxies work at the system level.

Features
Multiple Proxies: Redirects requests to various backend servers.
Round Robin Load Balancing: Distributes client requests evenly across multiple servers.
Concurrency: Handles multiple client connections using multi-threading.
Error Handling: Manages server connection errors and client timeouts.
Configurable Settings: Easily add or remove proxy servers via configuration.
Logging: Tracks all server activity for monitoring and debugging purposes.
Requirements
To run this project, you need the following:

A C compiler (e.g., gcc)
Basic POSIX libraries for networking (<netinet/in.h>, <arpa/inet.h>, <pthread.h>, etc.)
Multi-threading support
