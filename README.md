# Tutorial 10 (Broadcast)

## Reflection

### 2.1. Original code of broadcast chat

![](assets/2.1.png)

Start the server by executing `cargo run --bin server` in your terminal. Next, open three separate terminals and `run cargo run --bin client` in each one to start three clients. Each client, upon connecting, is greeted with a welcome message from the server and prompted to type a message. When a client sends a message, the message is broadcast to all connected clients as well as echoed back by the server.