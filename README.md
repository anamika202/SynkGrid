# SynkGrid
# ⚡ SyncGrid Arena

A sleek, serverless, real-time multiplayer Tic-Tac-Toe web application. Built for instant browser-to-browser synchronization without backend server overhead.

---

## 🌟 Features

- **Real-Time Online Multiplayer:** Low-latency match synchronization powered by MQTT over secure WebSockets (WSS).
- **Zero Configuration:** Players simply share a custom Room Code to link up and play instantly.
- **Pass & Play (Local Mode):** Seamless offline 2-player toggle for instant dual play on a single screen.
- **Responsive Dark UI:** Designed with an accessible, mobile-first slate interface with real-time turn cues.

---

## 🛠️ Tech Stack

- **Frontend:** Vanilla HTML5, CSS3, JavaScript (ES6)
- **Messaging Protocol:** MQTT via Paho JavaScript Client
- **Broker Relay:** HiveMQ Secure Public WebSocket Broker (`broker.hivemq.com:8884`)
- **Hosting:** GitHub Pages

---

## 🚀 How to Play

### Online Rooms
1. Open the game link on two different devices or tabs.
2. Enter the same Room Name (e.g. `arena99`) on both screens.
3. Tap **Join Game**.
   - Player 1 automatically takes **X** (First Turn).
   - Player 2 connects as **O**.
4. Tap grid cells to make moves and battle for 3-in-a-row!

### Pass & Play
- Switch to the **Pass & Play (Local)** tab at the top to play immediately with a friend on the same screen without network pairing.

---

## 📄 License
MIT License
