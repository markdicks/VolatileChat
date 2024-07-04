# VolatileChat

## Project Description
VolatileChat is an end-to-end encrypted text chat application designed for those who prioritize privacy and data security. Messages in VolatileChat are stored exclusively in RAM during the chat session and are never written to disk, ensuring all communication is ephemeral. Once a chat session is closed or a connection is lost, all messages are irrevocably deleted.

## Features
- **End-to-End Encryption:** Messages are encrypted on the sender's device and can only be decrypted by the intended recipient.
- **In-Memory Storage:** All messages are stored only in RAM and are never persisted to disk, ensuring they are wiped automatically when the chat session ends.
- **Secure Connection:** Utilizes TLS to secure the communication channel against eavesdropping and tampering.
- **No Persistence:** Messages are not stored beyond the life of the chat session, supporting use cases where data retention needs to be minimized.

## Installation
1. Clone the repository:
```
git clone https://github.com/markdicks/VolatileChat.git
```
2. Navigate to the project directory:
```
cd VolatileChat
```
3. Install Rust and Cargo (if not already installed):
```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```
4. Build the project:
```
cargo build --release
```
5. Run the application:
```
cargo run
```

## Usage
After launching the application, users can create a new chat session and invite others to join via a secure link. Messages will appear in real-time and will not be stored or retrievable after the session ends.

## Contributing
Contributions are welcome! Please read `CONTRIBUTING.md` for details on our code of conduct, and the process for submitting pull requests to us.

## Security
VolatileChat prioritizes security and privacy. If you discover a security issue, please refer to `SECURITY.md` on how to report it responsibly.

## License
This project is licensed under the MIT License - see the `LICENSE.md` file for details.

## Acknowledgments
- Thanks to all contributors who help in maintaining and improving this project.
- Special thanks to the Rust community for providing extensive resources and libraries for secure application development.

