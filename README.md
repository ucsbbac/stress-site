# 🌿 AI Stress Checker · AI 壓力檢測小幫手

Bilingual (EN/中文) AI stress checker. Users need no API key — yours is stored securely as an environment variable on Vercel.

## Files
```
stress-site/
├── index.html        ← entire frontend
├── api/
│   └── analyze.js    ← serverless function (hides your API key)
├── vercel.json       ← routing config
└── README.md
```

## Deploy in 5 minutes (free)

### Step 1 — Get a free Groq API Key
1. Go to https://console.groq.com/keys
2. Sign up free (email only, no credit card)
3. Click "Create API Key" → copy it

### Step 2 — Deploy to Vercel
1. Go to https://vercel.com → sign up free
2. Click "Add New" → "Project"
3. Click "Upload" and drag this entire `stress-site` folder
4. Before clicking Deploy, go to **Environment Variables**:
   - Name: `GROQ_API_KEY`
   - Value: paste your key from Step 1
5. Click **Deploy** ✅

Your site is live at `your-project.vercel.app` — share with anyone!

## Update the site
- Edit `index.html` locally
- Go to Vercel dashboard → your project → Deployments → upload again
- Or connect to GitHub for automatic deploys on every save

## Add a custom domain
Vercel dashboard → your project → Settings → Domains → add `stresscheck.yourdomain.com`
