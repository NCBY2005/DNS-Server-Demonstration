# DNS-Server-in-Rust

**Rust DNS Server**

A simple and efficient DNS server built in Rust. This DNS server handles DNS queries, resolves domain names, and returns IP addresses following standard DNS protocol specifications. Built with Rust’s focus on performance and safety, this server provides a fast, secure, and concurrent DNS service.

**Features**
------------

**Efficient Query Handling:** Handles DNS queries with a minimal response time.

**Caching:** Implements DNS response caching to speed up recurring requests.

**Concurrency:** Leverages Rust's async capabilities to manage multiple queries simultaneously.

**Configurable Settings:** Allows customizable settings for server configuration.

**Logging and Debugging:** Logs requests and errors for monitoring and troubleshooting.



**Configuration**
--------------------
The server can be configured through the config.toml file, where you can adjust:

**Port:** The port the server listens on (default is 2053).
