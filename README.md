📱 Expo Peer-to-Peer Chat App

A blazing-fast, lightweight peer-to-peer chat application built with React Native and powered by Expo. This app allows users to communicate in real-time directly with one another — no central servers required.

Designed to be private, offline-capable, and platform-agnostic, this project demonstrates the power of modern mobile development with local-first technologies like WebRTC, local SQLite storage, and peer discovery using local networks or QR codes.

🔑 Key Features

🔄 Real-Time Messaging — Instant delivery of messages via peer-to-peer connections.

📶 Offline Support — View chat history and cached data without an internet connection.

🔐 Privacy Focused — No central server; all messages are sent device-to-device.

📡 Peer Discovery — Connect with other users via QR code scanning or local network.

🧠 Message History — Persistent chat logs using SQLite or local storage.

📱 Cross-Platform — Works seamlessly on both Android and iOS via Expo.

🚀 Technologies Used

React Native (with Expo)

WebRTC or Multipeer Connectivity (iOS) / Wi-Fi Direct (Android) for P2P

Drizzle ORM + SQLite for local database storage (optional)

React Navigation for routing

Zustand / Redux for lightweight state management

Socket or direct data channels for message transfer (depending on platform)

🛠 Use Cases

🌍 Chat without the internet (in local environments like events, meetups, or emergencies)

🔐 Decentralized private communication

📦 Base for more complex decentralized apps (DApps)

📸 Screenshots

Coming soon — include chat screen, QR scanner, peer list, etc.

📦 Project Structure
project-root/
├── app/
│   ├── _layout.tsx
│   ├── index.tsx
│   └── chat/
│       ├── [peerId].tsx
├── src/
│   ├── db/             # Local SQLite schema and access
│   ├── hooks/
│   ├── components/
│   ├── services/       # Peer connection logic (WebRTC, etc.)
│   └── utils/
├── assets/
├── drizzle.config.ts
├── babel.config.js
└── metro.config.js

🧪 Development & Testing

Clone the repository:

git clone https://github.com/your-username/expo-p2p-chat.git
cd expo-p2p-chat


Install dependencies:

npm install


Start the Expo dev server:

npx expo start


Open on Android, iOS, or Web.

🤝 Contributing

Got ideas or bug reports? PRs and issues are welcome! This app is meant to be a base for further development in offline and decentralized mobile communication.

📄 License

MIT License. Feel free to use, modify, and share under the terms of the license.

❤️ Acknowledgements

Expo

React Native

Drizzle ORM

React Native WebRTCA Peer to Peer Messaging App

