# Realtime Demo

This project demonstrates real-time communication using WebSockets and OpenAI's Function Calling API. It is designed as a minimal example to show how you can build an interactive, real-time system powered by AI responses.

## 🚀 Features

- 🔌 WebSocket server for real-time messaging
- 🤖 Integration with OpenAI's Function Calling API
- 🛠️ Simple, readable Node.js backend

## 📦 Installation

1. **Clone the repository**

```bash
git clone https://github.com/crisperpo/realtime-demo.git
cd realtime-demo
```

2. **Install dependencies**

```bash
npm install
```

3. **Set up environment variables**

Create a `.env` file in the root directory and add your OpenAI API key:

```
OPENAI_API_KEY=your-api-key-here
```

## 🏃 Usage

Start the WebSocket server:

```bash
node index.js
```

Clients can connect to `ws://localhost:3000` to send and receive messages.

## 💡 Example Workflow

1. Client sends a message via WebSocket.
2. The server processes the message using OpenAI's function calling API.
3. The response (including structured function output) is sent back to the client in real time.

## 📝 License

MIT License
Built by [@crisperpo](https://github.com/crisperpo) with 💡
