# StyleBot (first version)

AI personal stylist web app: chat with a Gemini-powered stylist for outfit ideas for any occasion and budget, and shop the suggested looks. Includes login, terms and privacy pages.

This is the earlier version of [AI_style_bot_2](https://github.com/Amrittr/AI_style_bot_2).

## Run locally

```bash
npm install
cp .env.example .env   # then add your Gemini API key
npm start
```

On Vercel, set `GEMINI_API_KEY` in the project's Environment Variables.

Then open http://localhost:3000.

## Stack

Node.js + Express server (`server.js`) serving the pages in `public/` and proxying chat requests to the Gemini API. Deployed on Vercel (`vercel.json`).
