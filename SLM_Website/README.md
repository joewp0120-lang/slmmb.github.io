# SLM Masterbatches Website

This is a static corporate website for SLM Masterbatches Co., Ltd.

## Structure
- **index.html**: Home page
- **products.html**: Product catalog
- **about.html**: Company information
- **applications.html**: Industry applications
- **quality.html**: QC process
- **news.html**: News articles
- **contact.html**: Contact info and form
- **css/**: Stylesheets
- **js/**: JavaScript logic

## Domain Configuration (www.slmmb.com)

This project is configured for the domain: `www.slmmb.com`

### Files Created
- **CNAME**: Contains `www.slmmb.com` (required for GitHub Pages).
- **robots.txt**: Points search engines to the sitemap.
- **sitemap.xml**: Lists all pages with the `https://www.slmmb.com` prefix.
- **Canonical Tags**: All HTML pages include `<link rel="canonical" ...>` pointing to the correct URL.

### DNS Setup
To make the website accessible at `www.slmmb.com`, you need to configure your DNS records at your domain registrar (e.g., GoDaddy, Namecheap, Aliyun):

1.  **A Record**: Point `@` (root domain) to your hosting provider's IP address (see provider instructions).
2.  **CNAME Record**: Point `www` to your hosting provider's target domain (e.g., `cname.vercel-dns.com` for Vercel, or `your-site-name.netlify.app` for Netlify).

### Hosting Provider Setup

#### Vercel
1.  Go to your project dashboard > Settings > Domains.
2.  Add `www.slmmb.com`.
3.  Vercel will provide the correct A and CNAME records to add to your DNS.

#### Netlify
1.  Go to Site Settings > Domain Management.
2.  Add `www.slmmb.com`.
3.  Follow the instructions to verify ownership and configure DNS.

## Deployment

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in this directory.
3. Follow the prompts.

### Netlify
1. Drag and drop this folder to Netlify Drop, or connect via Git.

## Customization
- Edit `css/style.css` for colors and fonts.
- Edit HTML files for content.
- Images are currently hotlinked from Unsplash. For production, download them to `assets/images/` and update paths.
