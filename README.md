# Peoria Home Leads Website

A lead generation website for home services in Peoria, AZ.

## Pages

- `index.html` - Main landing page with lead form
- `roofing.html` - Roofing-specific landing page
- `hvac.html` - HVAC-specific landing page
- `general-contracting.html` - General contractor landing page
- `leads.html` - Buyer-facing lead sales page

## Deployment to GitHub Pages

1. Create a GitHub account at https://github.com
2. Create a new repository named `peoriahomeleads`
3. Push this repository to GitHub:
   ```
   git remote add origin https://github.com/YOUR_USERNAME/peoriahomeleads.git
   git push -u origin master
   ```
4. Go to your repository settings → Pages
5. Select "Deploy from a branch" → "Main" → "Root"
6. Your site will be live at `https://YOUR_USERNAME.github.io/peoriahomeleads/`

## Lead Form

The lead form uses FormSubmit (https://formsubmit.co) to send leads to `orichidia@gmail.com`.

**Important:** After the first form submission, you'll receive an email from FormSubmit asking you to confirm your email address. Click the confirmation link to activate the form.

## Custom Domain

To use `peoriahomeleads.com` instead of the GitHub Pages URL:

1. Buy the domain at a registrar (e.g., Namecheap, GoDaddy)
2. In your GitHub repository settings → Pages, enter your custom domain
3. Configure your domain registrar to point to GitHub Pages:
   - A record: `www` → `185.199.108.153`
   - A record: `www` → `185.199.109.153`
   - A record: `www` → `185.199.110.153`
   - A record: `www` → `185.199.111.153`
   - CNAME: `www` → `YOUR_USERNAME.github.io`

## SEO

The website includes:
- Meta descriptions and keywords for each page
- Canonical URLs
- Mobile-responsive design
- Fast loading (no external dependencies)

## Next Steps

1. Deploy to GitHub Pages
2. Buy the domain `peoriahomeleads.com`
3. Configure the custom domain
4. Set up Google Business Profile
5. Start driving traffic (Google Ads, local directories, social media)
6. Collect leads and sell them to local businesses
