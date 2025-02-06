# Codename

A multiplayer card game built with the MERN stack (MongoDB, Express, React, Node.js) featuring real-time gameplay through websockets.

## 🛠️ Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Real-time Communication**: Socket.IO
- **Deployment**: Backend on Heroku, and Frontend on Nelify

## 📋 Prerequisites

- Node.js and npm ([Download](https://nodejs.org/))
- MongoDB Atlas account ([Setup Guide](https://www.mongodb.com/cloud/atlas/register))
- Yarn package manager (`npm install -g yarn`)

## 🚀 Getting Started

1. Clone the repository:
```bash
git clone [repository-url]
cd [project-directory]
```

2. Environment Setup:
```bash
# Create .env file in server directory
echo "DB_URL=your_mongodb_url" > server/.env
```

3. Install Dependencies:
```bash
# Client setup
cd client
yarn install

# Server setup
cd ../server
yarn install
```

4. Run the Application:
```bash
# Start client (in client directory)
yarn start

# Start server (in server directory)
yarn start
```

## 📝 Development Process

### Planning Phase
- Weekly goal setting and milestone tracking
- Initial framework implementation focusing on:
  - Turn-based mechanics
  - Card state management
  - Basic board layout
- Single-device gameplay testing
- Multiplayer implementation via WebSocket

### Technical Challenges
- WebSocket integration for real-time gameplay
- MERN stack learning curve
- Frontend-Backend integration
- Cross-device compatibility
- Time management and team coordination
