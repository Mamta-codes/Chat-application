# Chat-application
pikaTalk is a modern real-time group chat application built using HTML, CSS, JavaScript, Node.js, and Socket.io. It allows multiple users to join a chatroom, send messages instantly, view who is online, and see typing indicators — creating a smooth and interactive chatting experience similar to WhatsApp Web or Discord.

🚀 Key Features
🔹 1. Real-Time Messaging

Messages are delivered instantly using Socket.io WebSocket communication.

Supports sending and receiving text messages without any page refresh.

🔹 2. Username-Based Login

Users must enter a username before joining the chatroom.

Once joined, everyone can see that the user has entered the chat.

🔹 3. Chat History (Persistent Messages)

New users can see all previous chats as soon as they join.

Messages are stored in server memory (messages[] array).

🔹 4. Online Users List

Live count of users currently online.

Dynamic list showing all active users in the chatroom.

🔹 5. Typing Indicator

Shows “username is typing…” when someone is typing.

Disappears automatically when they stop.

🔹 6. Join and Leave Notifications

All users receive alerts when someone enters or leaves the chat.

🔹 7. Notification Sound

A soft sound plays whenever someone else sends a new message.

Sound does not play on your own messages.

🔹 8. Modern UI + Dark/Light Theme

Clean chat interface inspired by modern messaging apps.

One-click theme toggle stored in localStorage.

🔹 9. Safe HTML Rendering

All messages are sanitized using escapeHtml() to prevent HTML/script injections.

🧩 Tech Stack
Frontend:

HTML

CSS

JavaScript

Socket.io Client

Backend:

Node.js

Express

Socket.io Server

🛠️ How It Works

User opens the app → enters username

Client connects to the Socket.io server

Server stores username and sends:

Chat history

Online users list

User sends messages → broadcasted to all other users

Typing and online status updates are handled in real-time

📌 Use Cases

Real-time team communication

Group study chats

Event discussion rooms

Hackathons & Coding communities

Live Q&A support chat

🎯 Project Highlights

This project demonstrates strong understanding of:

WebSockets

Event-driven architecture

Real-time broadcast systems

Frontend + backend integration

UI/UX design for chat applications
