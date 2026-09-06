# SDS UZ INC — Dispatch CRM

Real React + Vite project (not a sandboxed chat artifact), connected to your
Supabase project. This runs in your own browser tab, so it can actually
reach the internet — no CORS/sandbox restrictions.

## Option A — Deploy to Vercel (easiest, no terminal needed)

1. Go to https://vercel.com and sign up (GitHub login is easiest).
2. Click "Add New" → "Project" → "Deploy without Git" (or drag-and-drop
   this whole folder onto the Vercel dashboard import screen).
3. Vercel auto-detects Vite. Leave the defaults and click Deploy.
4. In a minute or two you'll get a live URL — that's your real site.

## Option B — Run locally

Requires Node.js (https://nodejs.org, LTS version) installed once.

```bash
cd sds-uz-crm
npm install
npm run dev
```

Then open the local URL it prints (usually http://localhost:5173).

## Option C — Ask Claude Code to do it for you

If you have Claude Code installed, you can hand it this whole folder and
say "install dependencies and deploy this to Vercel" — it can run the
terminal commands for you.

## Supabase

The Supabase URL and publishable key are already wired into `src/App.jsx`
(search for `SUPABASE_URL`). Nothing else to configure — as long as you've
run `supabase-schema.sql` in your project's SQL Editor, sign up on the
login screen and you're in.
