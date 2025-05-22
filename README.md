# Todo Summary Assistant

## Setup Instructions

### Backend
1. `cd backend`
2. `npm install`
3. Create `.env` using `.env.example`
4. `node index.js`

### Frontend
1. `cd frontend`
2. `npm install`
3. `npm start`

### Slack and LLM Setup
- Get OpenAI API key from https://platform.openai.com
- Create Slack Incoming Webhook from https://api.slack.com/messaging/webhooks

### Architecture
React frontend connects to Express backend with endpoints for todos and summary.
