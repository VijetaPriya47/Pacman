# Pacman Multiplayer Game 🎮🍒

Welcome to the **Pacman Multiplayer Game**! Dive into the nostalgic world of Pacman with a modern twist—now you can enjoy this classic arcade game with a friend in real-time! Thanks to Socket.IO, you and your buddy can navigate the maze, munch on pellets, and outwit each other in this thrilling two-player experience.

## 🌟 Features

- **Classic Pacman Fun**: Relive the magic of Pacman with enhanced graphics and gameplay.
- **Real-Time Multiplayer**: Challenge a friend to a duel in the maze, with live updates of each other's moves.
- **Seamless Interaction**: Enjoy smooth, real-time communication between players thanks to Socket.IO.
- **Node.js Backend**: A robust server that handles game logic and player interactions.

## 🚀 Getting Started

Follow these steps to get up and running with Pacman Multiplayer:

### Prerequisites

- [Node.js](https://nodejs.org/) - JavaScript runtime for server-side code
- [npm](https://www.npmjs.com/) - Node package manager

### Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/VijetaPriya47/Pacman.git
   cd Pacman
   ```

2. **Install Dependencies**

Install the required Node.js packages:

```bash
npm install
```
3. **Start the Server**

Launch the server to manage game state and player interactions:

```bash
node server.js
```
4. **Open the Game **

Open index.html in your web browser. To play, open another browser window or tab to start a second player session.

## 🎮 How to Play
**Movement:** Use the arrow keys to guide your Pacman through the maze.
**Pellets:** Munch on pellets to score points and evade ghosts.
**Multiplayer Fun:** Compete with your friend to see who can score the most points.
## 🔧 *Socket.IO Integration*
The game leverages **Socket.IO** for real-time multiplayer functionality. Here’s what the server code, located in server.js, does:

**Player Management:** Keeps track of all connected players.
**Movement Synchronization:** Broadcasts player movements to ensure everyone sees the same game state.
**Disconnection Handling:** Notifies all clients when a player disconnects.

## 🤝 Contributing
We welcome contributions! Whether you’re fixing bugs, adding features, or improving gameplay, your help is valuable. Please fork the repository and submit a pull request.

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for more details.

## ✉️ Contact
Have questions or suggestions? Reach out to:

Author: Vijeta Priya
GitHub: VijetaPriya47
Have a blast playing Pacman with your friends, and may the best player win! 🚀🍬




