# simple-stream

simple-stream is a lightweight open-source stream server and client written in C. The project demonstrates the fundamentals of network streaming using low-level socket programming, making it suitable for learning and experimentation with client–server communication.

---

## Installation Instructions

### Prerequisites
- A C compiler (such as gcc or clang)
- POSIX-compatible operating system (Linux or macOS)

### Build

1. Clone the repository:
   ```
    git clone https://github.com/NAU-OSS/simple-stream.git
2. Navigate into the project directory:
   ```
    cd simple-stream
4. Compile the server and client:
   ```
    gcc server.c -o server
    gcc client.c -o client
   ```

## Usage Examples

Start the stream server:
  ```
    ./server
  ```
Run the client in a seperate terminal:
  ```
    ./client
  ```
The client will connect to the server and recieve a data stream.

## Project Status and Roadmap
**Status:** Active (school project)

**Roadmap:**
- Improve error handling and the input validation.
- Support for cocurrent clients to join (chat-room similarity)
- Username capabilities.

## Contact and Community
- **Github Issues:** Use the issue tracker for bug reports and feature requests.
- **Dicussions:** Use GitHub Discussions for questions/ideas.

Any contributions are welcome!



