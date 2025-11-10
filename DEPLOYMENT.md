# Deployment Guide

## Base44 Cloud Deployment

This app is built on Base44 and can be deployed with one click:

```bash
base44 deploy
```

## Environment Variables

Create a `.env` file:

```
BASE44_APP_ID=your_app_id
BASE44_API_KEY=your_api_key
```

## Docker Deployment

```bash
docker build -t codeforge .
docker run -p 3000:3000 codeforge
```

## Vercel/Netlify

1. Connect your GitHub repository
2. Set build command: `npm run build`
3. Set output directory: `dist`
4. Deploy!
