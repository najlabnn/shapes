
# Shape Backend API (Node.js + Express)

This is a simple backend API that securely connects to OpenAI's DALL·E API to generate shape images.

## Setup locally

1. Clone the repo.
2. Install dependencies:
```
npm install
```
3. Set your environment variable (create `.env` file or set OPENAI_API_KEY).
4. Run the server:
```
node server.js
```

## Deploy to Vercel

1. Push the code to GitHub.
2. Go to https://vercel.com and create a new project.
3. Link your GitHub repo.
4. Add Environment Variable:
   - `OPENAI_API_KEY`: Your OpenAI API Key
5. Deploy.

## Deploy to Render

1. Push the code to GitHub.
2. Go to https://render.com and create a new Web Service.
3. Connect your repo.
4. Set:
   - Environment: Node
   - Start Command: `node server.js`
   - Environment Variable: `OPENAI_API_KEY`
5. Deploy.

## Frontend Example

Use `chatbot.html` as your frontend.
Update the API URL in the JS code to your deployed backend.
