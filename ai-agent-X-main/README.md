# MCP Server Project

This project consists of a client-server architecture with separate components for the server and client applications. The application features an AI-powered Twitter post creation system that helps users generate engaging and relevant content for their Twitter feed.

## Features

- AI-powered Twitter post generation
- Client-server architecture for scalable deployment
- Real-time content generation
- User-friendly interface

## Technologies Used

### Frontend
- React.js - Modern UI library for building user interfaces
- Material-UI - Component library for consistent design
- Redux - State management
- Axios - HTTP client for API requests
- Socket.io-client - Real-time communication

### Backend
- Node.js - Runtime environment
- Express.js - Web framework
- OpenAI API - AI content generation
- Twitter API - Social media integration
- Socket.io - Real-time bidirectional communication
- MongoDB - Database for storing user data and post history
- JWT - Authentication and authorization

### Development Tools
- Git - Version control
- npm - Package management
- ESLint - Code linting
- Jest - Testing framework
- Docker - Containerization

## Project Structure

```
mcp-server/
├── client/     # Client application
├── server/     # Server application
└── .gitignore  # Git ignore configuration
```

## Getting Started

### Prerequisites

- Node.js (version 14 or higher recommended)
- npm or yarn package manager
- Twitter Developer Account (for API access)
- OpenAI API Key
- MongoDB instance

### Installation

1. Clone the repository:
```bash
git clone https://github.com/adityaAK47/ai-agent-X.git
cd mcp-server
```

2. Install server dependencies:
```bash
cd server
npm install
```

3. Install client dependencies:
```bash
cd ../client
npm install
```

### Configuration

1. Set up your environment variables:
   - Create a `.env` file in the server directory
   - Add your API credentials:
   ```
   # Twitter API Credentials
   TWITTER_API_KEY=your_api_key
   TWITTER_API_SECRET=your_api_secret
   TWITTER_ACCESS_TOKEN=your_access_token
   TWITTER_ACCESS_SECRET=your_access_secret

   # OpenAI API
   OPENAI_API_KEY=your_openai_api_key

   # MongoDB
   MONGODB_URI=your_mongodb_connection_string

   # JWT
   JWT_SECRET=your_jwt_secret
   ```

### Running the Application

1. Start the server:
```bash
cd server
npm start
```

2. Start the client:
```bash
cd client
npm start
```

## Development

- The server application is located in the `server/` directory
- The client application is located in the `client/` directory

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 