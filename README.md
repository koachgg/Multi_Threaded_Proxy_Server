# Multi-Threaded Proxy Server with Cache

Welcome to the Multi-Threaded Proxy Server project! This project demonstrates the implementation of a proxy server with and without caching using C. It handles HTTP requests, supports multiple threads for concurrent connections, and utilizes an LRU (Least Recently Used) caching mechanism to optimize performance.

## Table of Contents

- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- Multi-threaded proxy server handling multiple client connections simultaneously.
- HTTP request parsing and response handling.
- Caching mechanism using the Least Recently Used (LRU) algorithm.
- Configurable cache size to balance performance and memory usage.
- Ability to handle concurrent requests and responses efficiently.

## Tech Stack

- **C**: Programming language used for implementation.
- **HTTP Parsing**: Handling HTTP requests and responses.
- **Multi-threading**: Utilizing threads to handle concurrent connections.
- **Caching**: Implementing the Least Recently Used (LRU) caching algorithm.

## Installation

To get started with the proxy server, follow these steps:

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/multi-threaded-proxy-server.git
    cd multi-threaded-proxy-server
    ```

2. **Compile the code:**

    ```bash
    gcc -o proxy server.c -lpthread
    ```

    Replace `server.c` with the name of your C source file if different.

3. **Run the proxy server:**

    ```bash
    ./proxy
    ```

    Ensure that you have the necessary permissions and configurations to run the server.

## Usage

- The proxy server will start listening for HTTP requests on the specified port.
- You can configure the cache size by modifying the source code or providing command-line arguments if supported.
- Use your browser or any HTTP client to make requests through the proxy server.

## Contributing

If you'd like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push your branch (`git push origin feature-branch`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to adjust the instructions and details according to your project’s specifics and additional functionalities.
