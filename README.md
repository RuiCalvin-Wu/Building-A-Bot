# 🧠 Build-a-Bot for Entelect Challenge 2025

Welcome to my Build-a-Bot project, created for the **Entelect Challenge 2025**. This bot was developed to compete in the Zooscape game scenario, where autonomous agents (a.k.a. bots) navigate mazes, collect pellets, dodge zookeepers, and maximize their score.

> 🌐 [Official Challenge Info](https://l.ead.me/build-a-bot-2025)

## 🚀 Project Overview

This project features:
- A **.NET 8**-based bot using SignalR for real-time communication with the game engine
- A **Dockerized environment** to run the official Entelect game engine
- **GoDart** game visualizer for inspecting game state playback
- Adaptive strategy for navigating toward pellets, avoiding enemies, and leveraging power-ups

## 🧰 Tech Stack

| Tool/Tech        | Purpose                                  |
|------------------|------------------------------------------|
| `.NET 8 (C#)`    | Core bot logic & SignalR client          |
| `Docker`         | Hosting the official game engine         |
| `SignalR`        | Real-time communication with game engine |
| `GoDart`         | Game visualizer for replay debugging     |
| `Visual Studio Code` | Preferred IDE for development      |

## 📦 Setup Instructions

### Prerequisites

- [.NET 8 SDK](https://dotnet.microsoft.com/en-us/download)
- [Docker Desktop](https://www.docker.com/products/docker-desktop/)
- Git or ZIP download of the bot repo

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/build-a-bot-entelect-2025.git
cd build-a-bot-entelect-2025
