# Builder of Things / Bombaybot Website

Premium AI-first studio portfolio website.

## Files

- **index.html** - Primary v1 version (simpler, animated canvas + dark nav)
- **index-v2.html** - Primary v2 version (modern glassmorphism, advanced cursor)

## Features

✅ Advanced custom cursor (24px ring, 6px accent dot, glow effects)  
✅ Premium Phosphor Icons (6 studio tools)  
✅ Elegant typography with styled commas  
✅ "EVOLVE" hero text (replaced "CREATE")  
✅ Responsive, mobile-first design  

## Local Development

```bash
# Install dependencies
npm install

# Start local server
npm start
# or
npx http-server -p 8080
```

## Deployment

### Vercel (Recommended)

1. Connect your GitHub/GitLab repo to Vercel
2. Import this project
3. Deploy automatically (free tier available)

**Manual Vercel CLI:**
```bash
vercel login
vercel --prod
```

### Netlify

```bash
# Drag & drop the folder to Netlify Drop
# Or connect via Git for continuous deployment
```

### Static Hosting

Works with any static host (GitHub Pages, Cloudflare Pages, AWS S3, etc.)

## Custom Domain

After deploying, add your custom domain in the hosting platform's dashboard:

1. Go to your project dashboard
2. Navigate to "Domains" / "Custom Domains"
3. Enter your domain (e.g., `bom-bot.io` or `bom-bot.com`)
4. Follow DNS instructions (CNAME or A records)

## Browser Support

- Chrome 90+ ✅
- Firefox 88+ ✅
- Safari 14+ ✅
- Edge 90+ ✅
