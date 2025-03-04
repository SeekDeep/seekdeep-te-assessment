# Technical Task: Streaming Chat System

## Objective
Build a simple chat system where the backend sends streaming messages, and the frontend receives and displays them in real-time.

## Task Breakdown

### 1. Backend (Message Streaming Server)
- Create a server that continuously sends messages to connected clients.
- Use WebSockets to enable real-time communication.
- The backend should always send the same response, like "Hello from server!".
- Messages should be **streamed character by character** instead of sending the whole message at once.
- Recommended: Use **FastAPI** for easy WebSocket handling.

### 2. Frontend (Basic Chat UI)
- Create a simple webpage that connects to the WebSocket server.
- Display incoming messages in a chat-style interface.
- The messages in the chat should appear chunk-by-chunk and not as a whole (Like ChatGPT responses(word by word), not like Instagram(message as a whole))
- Messages from the server should appear **progressively in a chat bubble**, simulating a typing effect.
- Recommended: Use **React** to handle the real-time updates.

## Example

### UI/UX Example
- The chat interface should have a **header** displaying "Chat Messages".
- Messages should appear in a **scrollable chat window**.
- Each message should be inside a **bubble** with alternating colors for different senders.
- The latest message should always be visible at the bottom.
- A simple **input box** and **send button** can be included for future enhancements.
- Messages from the server should **appear gradually inside the chat bubble, as if being typed in real-time**.

**Example Layout:**
```
----------------------------------
|       Chat Messages           |
----------------------------------
| [User]: Hello!                |
| [Server]: Hello from server!  |
----------------------------------
```

## Deliverables
- A working backend that streams chat messages character by character over WebSockets.
- A frontend that connects to the backend and displays messages with a typing effect inside a normal chat bubble.
- A brief README explaining how to run both components.

Let me know if you have any questions!

