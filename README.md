# VOYAGE — Test Website 1 (Defect Set A)

> **"Go places. Feel everything."**
> Autonomous QA testing target containing 12 intentional, reproducible defects (A01–A12) including invalid return date bypass, omitted passenger counts, rogue flight injection, and sold-out room selection.

---

## Environment: Defect Set A Active

This repository contains the standalone, independent build of **VOYAGE** configured specifically for **voyage-test-website-1**.

---

## Quick Deploy to Vercel

### Option 1: Via GitHub & Vercel Dashboard (Easiest)
1. Create a new repository on your GitHub account named `voyage-test-website-1`.
2. Push this directory to your new GitHub repo:
   ```bash
   git remote add origin https://github.com/<YOUR-GITHUB-USERNAME>/voyage-test-website-1.git
   git branch -M main
   git push -u origin main
   ```
3. Go to [https://vercel.com/new](https://vercel.com/new), select your `voyage-test-website-1` repository, and click **Deploy**.
4. Vercel will automatically detect Vite and deploy your site in seconds!

### Option 2: Via Vercel CLI
```bash
npx vercel
# Follow the prompts and accept defaults (Vite Framework Preset)
```

---

## Local Development

```bash
# Install dependencies
npm install

# Start local development server
npm run dev

# Build production bundle
npm run build

# Preview production build locally
npm run preview
```
