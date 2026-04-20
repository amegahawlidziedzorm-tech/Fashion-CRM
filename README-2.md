# Atelier — Fashion Studio CRM

A luxury fashion designer CRM with Supabase authentication, built as a single-page PWA.

## Features
- Client management with style profiles & measurements
- Order tracking & status management
- Appointment booking
- Inventory management
- AI assistant (Aria) powered by Claude
- PWA — installable on mobile & desktop

## Setup

### 1. Supabase
1. Create a project at [supabase.com](https://supabase.com)
2. Copy your **Project URL** and **Anon Key**
3. Paste them into `index.html` where you see:
   ```js
   const SUPABASE_URL = 'YOUR_SUPABASE_URL';
   const SUPABASE_ANON_KEY = 'YOUR_SUPABASE_ANON_KEY';
   ```

### 2. Deploy on Netlify
- Connect this GitHub repo to Netlify
- No build command needed
- Publish directory: `.` (root)
- Deploy!

## File Structure
```
├── index.html        ← Main app (all HTML, CSS, JS)
├── manifest.json     ← PWA manifest
├── sw.js             ← Service worker (offline support)
├── netlify.toml      ← Netlify config
├── _headers          ← Security headers
└── README.md
```
