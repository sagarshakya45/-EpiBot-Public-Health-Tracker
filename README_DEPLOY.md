# EpiBot Deployment Guide

This app is a static single-page HTML chatbot.

## Files

- `public_health_chatbot_groq.html` - main chatbot page
- `index.html` - redirect entry point
- `netlify.toml` - Netlify config
- `vercel.json` - Vercel config

## Deploy on Netlify

1. Open Netlify and create a new site from drag-and-drop or Git.
2. Deploy the folder containing these files.
3. No build command is required.
4. Publish directory: root folder (`.`).

## Deploy on Vercel

1. Create a new Vercel project from this folder/repo.
2. Framework preset: `Other`.
3. No build command is required.
4. Output directory: leave default (root static files).

## Important Production Note

Current login is demo client-side auth (`sessionStorage`) and is not a secure server-side authentication system.
For real production security, integrate backend authentication (Auth0, Firebase Auth, Supabase Auth, or a custom backend).
