# Gemini Chatbot

A modern chatbot application powered by Google's Gemini API, featuring a responsive UI and conversation history.

## Features

- Real-time chat interface
- Conversation history with local storage
- Responsive design for all devices
- Markdown support in messages
- Typing indicators
- Delete conversation functionality

## Prerequisites

- Node.js >= 18.0.0
- Google Gemini API key

## Environment Variables

Create a `.env` file in the root directory with:

```
GEMINI_API_KEY=your_api_key_here
```

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create `.env` file with your API key
4. Start the development server:
   ```bash
   npm run dev
   ```

## Deployment

### Render

1. Create a new Web Service on Render
2. Connect your GitHub repository
3. Set the following:
   - Build Command: `npm install`
   - Start Command: `npm start`
4. Add your `GEMINI_API_KEY` to the environment variables
5. Deploy!

### Railway

1. Create a new project on Railway
2. Connect your GitHub repository
3. Add your `GEMINI_API_KEY` to the environment variables
4. Deploy!

### Heroku

1. Create a new app on Heroku
2. Connect your GitHub repository
3. Add your `GEMINI_API_KEY` to the environment variables
4. Deploy!

## Local Development

```bash
npm run dev
```

The application will be available at `http://localhost:3000`

## License

ISC 