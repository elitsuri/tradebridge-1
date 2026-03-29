# TradeBridge

> Desktop trading dashboard with real-time feeds and order execution

## ✨ Features
- User authentication with JWT
- CRUD operations for main resources
- RESTful API with proper status codes
- Database migrations and seed data
- Docker containerization

## 🧰 Tech Stack
Kotlin, Compose Desktop, PostgreSQL

## 🏗️ Architecture
Backend service with Kotlin, frontend user interface, and database persistence

## 🚀 Quick Start

### Prerequisites
- Docker & Docker Compose
- SQLite / PostgreSQL

### Setup

```bash
# Clone the repository
git clone https://github.com/elitsuri/tradebridge
cd tradebridge

# Copy environment variables
cp .env.example .env
```

### Run

```bash
docker compose up --build
```
