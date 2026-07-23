# PondyService.in — Deploy this live in ~15 minutes, no coding required

This folder is a real, working website project. I already ran `npm install` and
`npm run build` on it here — it compiles cleanly with zero errors. You do not
need Node.js, npm, or any coding tool on your own computer to launch it.

## Step 1 — Put the code on GitHub (5 minutes)
1. Go to github.com and create a free account if you don't have one.
2. Click "New repository." Name it `pondyservice-web`. Keep it Public or Private,
   either is fine. Click "Create repository."
3. On the next page, click "uploading an existing file."
4. Unzip `pondyservice-web.zip` on your computer, then **drag the whole folder's
   contents** (not the zip itself) into the GitHub upload box.
5. Scroll down, click "Commit changes." Done — your code is now on GitHub.

## Step 2 — Deploy it live with Vercel (5 minutes, free)
1. Go to vercel.com and sign up using your GitHub account (one click).
2. Click "Add New… → Project."
3. Select the `pondyservice-web` repository you just created.
4. Vercel will auto-detect it's a Vite project — leave every setting as default.
5. Click "Deploy."
6. Wait about a minute. Vercel gives you a live URL like
   `pondyservice-web.vercel.app` — that's your real, working website, live on
   the internet, for anyone to open.

## Step 3 — Point your own domain at it (optional, ~5 minutes)
1. Buy `pondyservice.in` from any registrar (GoDaddy, Namecheap, Hostinger, etc.)
   if you haven't already — roughly ₹800–1,500/year.
2. In Vercel, go to your project → Settings → Domains → add `pondyservice.in`.
3. Vercel shows you 1–2 DNS records to add. Log into your domain registrar,
   find "DNS settings," and add exactly what Vercel shows you.
4. Wait 10 minutes to a few hours for DNS to update. Your real domain now
   points to the live app.

## What you'll have at this point
A real, live, shareable website running the full demo — customer app,
technician app, admin panel, rental agreements, maps, everything we built.
Anyone with the link can open it on their phone or laptop right now.

## What this does NOT include yet (be clear-eyed about this)
- No real database — data resets when the page reloads. Every visitor sees
  the same starting demo data, not their own persistent bookings.
- No real payment collection — Razorpay isn't wired in yet.
- No real SMS — the OTP login is simulated (code `1234`).
- No real e-Stamp — that screen is clearly marked SPECIMEN/demo.

This step gets you a genuine, working, on-the-internet product you can show
investors, technicians, and early customers — the next step (a real backend +
Razorpay + real SMS) is a separate, bigger piece of work. Ask me when you're
ready for that and I'll build it the same way: for real, tested, step by step.
