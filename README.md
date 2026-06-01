# Notch Content Room Vercel Project

Folder structure:

```
notch_content_room_vercel_ready/
  index.html
  vercel.json
  api/
    generate.js
```

## Deploy notes

1. Upload or push this folder to Vercel.
2. In Vercel, add an environment variable called `GEMINI_API_KEY`.
3. The page calls `/api/generate`. The API route uses Gemini and returns an Anthropic-style `content` array so the existing front-end parser works.

