# PickSpin Legal (Privacy Policy)

This project is meant to be the contents of the **pickspin-legal** GitHub repository. Deploy it with Vercel to host the privacy policy page.

## Option A: Deploy from GitHub (recommended)

1. Push this folder’s contents to your **pickspin-legal** repo (use this folder as the repo root, so `index.html` is at the root):
   ```bash
   cd privacy-site
   git init
   git add .
   git commit -m "Initial commit: privacy policy page"
   git remote add origin https://github.com/YOUR_USERNAME/pickspin-legal.git
   git branch -M main
   git push -u origin main
   ```
2. Go to [vercel.com/new](https://vercel.com/new).
3. **Import** your **pickspin-legal** repository (sign in with GitHub if needed).
4. Leave the default settings and click **Deploy**. Vercel will build and give you a URL (e.g. `https://pickspin-legal.vercel.app`).

Every push to `main` will trigger a new deploy.

## Option B: Deploy with Vercel CLI from this folder

```bash
cd privacy-site
npx vercel
```

Follow the prompts; you’ll get a URL when the deploy finishes.

## Option C: Upload from Vercel dashboard

1. Go to [vercel.com/new](https://vercel.com/new).
2. Use **Upload** or drag-and-drop this `privacy-site` folder.
3. Click Deploy.

---

After deploy, use the Vercel URL as the **Privacy Policy URL** in App Store Connect and optionally link to it from the app.
