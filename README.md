# Kaam Connect starter

A mobile-friendly React + Vite starter for the Kaam Connect marketplace.

## Run locally
1. Install Node.js (LTS): https://nodejs.org/
2. Extract this ZIP.
3. Open a terminal in this folder and run:
   ```bash
   npm install
   npm run dev
   ```
4. Open the local URL shown by Vite.

## Deploy to Vercel
1. Push this folder to a GitHub repository.
2. In Vercel, choose **Add New → Project** and import that GitHub repository.
3. Framework preset: Vite. Build command: `npm run build`. Output directory: `dist`.
4. Click Deploy.

## Important limitations
This is a frontend starter, not a production marketplace. Profiles and job posts are stored only in the current browser's localStorage. Login, real-time chat, cross-device database sync, hire requests, payments, moderation, and admin tools are not connected yet. Add Supabase and security policies before inviting real users.
