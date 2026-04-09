# 🏀 BasketBallBox

A 1v1 3D basketball game you play in the browser. No game engine. Try it at [basketballbox.xyz](https://basketballbox.xyz).

You sign in, create or join a room, and play against someone live. Rooms can be public or private with a password. You pick casual or competitive mode and choose a score target: first to 5, 7, 11, or 21. Players have accounts, earn coins, and can buy skins from a shop.

The 3D client runs in the browser using Three.js with animated GLB player models. Game state syncs over WebSockets.

## This repo

This is the backend. The frontend is private. What's here:

- WebSocket server that manages game sessions
- Room logic including passwords, modes, and score targets
- Firebase auth
- Coins system
- Shop system
- Player animation files (GLB)

## Tech

- Node.js
- WebSockets
- Firebase
