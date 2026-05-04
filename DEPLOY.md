# Deployment Instructions

## Vercel (Recommended) 🌐

### Quick Deploy (3 minutes)

```bash
# Install Vercel CLI
npm install -g vercel

# Login
vercel login

# Deploy to production
cd /Users/sambombay/builder-of-things
vercel --prod
```

### Connect Custom Domain

1. After deployment, go to your Vercel dashboard
2. Project → Settings → Domains
3. Add domain (e.g., `bom-bot.io`)
4. Follow DNS setup instructions

### GitHub Deploy

```bash
# Initialize git
git init
git add .
git commit -m "Initial commit"

# Create GitHub repo and push
gh repo create bom-bot --public --source=. --remote=origin
git push -u origin main
```

Then import on https://vercel.com/new

---

## IONOS Deployment 🏢

### Option 1: FTP Upload

```bash
# Connect via FTP
ftp your-domain.ionos.com

# Upload files to /httpdocs or /www directory
put index.html
put index-v2.html
```

### Option 2: WebFTP

1. Login to IONOS Control Panel
2. Go to "My Products" → "Web hosting"
3. Click "Manage" → "FTP & Database"
4. Use WebFTP or FTP credentials to upload files

### Option 3: Git Deploy

If using IONOS DevCenter:

```bash
git remote add ionos ssh://user@ssh.ionos.com/~/html
git push ionos main
```

### Option 4: Point IONOS DNS → Vercel

1. In IONOS DNS Console, add:
   ```
   Type: CNAME
   Host: www
   Points to: cname.vercel-dns.com
   TTL: 3600
   ```

2. In Vercel, add domain `www.your-domain.com`

---

## Netlify Deploy 🚀

### Drag & Drop

1. Go to https://app.netlify.com/drop
2. Drag `/Users/sambombay/builder-of-things` folder
3. Done!

### Git Deploy

```bash
git init
git add .
git commit -m "Deploy"
git push
```

Connect repo on Netlify dashboard.

---

## Local Preview

```bash
cd /Users/sambombay/builder-of-things
npm start
# Visit: http://localhost:8080
```

Or with Python:

```bash
cd /Users/sambombay/builder-of-things
python3 -m http.server 8080
```

---

## File Checklist

- ✅ `index.html` - Main page (v1)
- ✅ `index-v2.html` - Main page (v2)
- ✅ `package.json` - NPM config
- ✅ `vercel.json` - Vercel settings
- ✅ `README.md` - Documentation

All dependencies: **None** (CDN only: Phosphor Icons)

---

## Post-Deployment

### Test Checklist

- [ ] Visit `https://your-domain.com`
- [ ] Test cursor on all devices
- [ ] Verify Phosphor icons load
- [ ] Check mobile responsiveness
- [ ] Test all links
- [ ] Enable HTTPS (automatic on Vercel/Netlify)

### Performance

Expected load time: < 1s (all assets inline)

---

## Need Help?

- Vercel Docs: https://vercel.com/docs
- IONOS Help: https://www.ionos.com/help
- Netlify Docs: https://docs.netlify.com
