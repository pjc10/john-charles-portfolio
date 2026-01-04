# John Charles Portfolio - Cloned Site

This is a cloned version of the portfolio website from https://john-charles.com/, prepared for deployment on Vercel or another static hosting provider.

## Site Structure

The site includes the following main pages:
- **Home** (`/`) - Advertising & Digital portfolio
- **Creative Technology** (`/tech/`) - Technology projects
- **Content** (`/content/`) - Content work
- **UX, Product & Experience Design** (`/product-ux/`) - UX/Product design projects
- **About** (`/about/`) - About page

Additionally, there are numerous portfolio project pages under `/work/`.

## Assets

All assets have been downloaded and organized:
- **CSS**: `/wp-content/themes/semplice/css/`
- **JavaScript**: `/wp-includes/js/` and theme-specific JS
- **Images**: `/wp-content/uploads/`
- **Fonts**: Included in theme assets

## Deployment Instructions

### Deploy to Vercel

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm install -g vercel
   ```

2. **Deploy from this directory**:
   ```bash
   cd /Users/laptop/dev/jchs/portfolio-clone/john-charles.com
   vercel deploy
   ```

3. **Follow the prompts** to link to your Vercel account and configure the project.

4. **For production deployment**:
   ```bash
   vercel --prod
   ```

### Alternative: Deploy via Vercel Dashboard

1. Push this directory to a Git repository (GitHub, GitLab, or Bitbucket)
2. Go to [vercel.com](https://vercel.com) and sign in
3. Click "New Project"
4. Import your Git repository
5. Vercel will automatically detect the static site and deploy it

### Deploy to Other Providers

This is a static HTML site and can be deployed to any static hosting provider:
- **Netlify**: Drag and drop the `john-charles.com` folder
- **GitHub Pages**: Push to a GitHub repository and enable Pages
- **AWS S3**: Upload files to an S3 bucket configured for static hosting
- **Cloudflare Pages**: Connect your Git repository

## Notes

- All links have been converted to relative URLs for portability
- The site is fully static and doesn't require a backend
- Some WordPress-specific features (like search or comments) won't work as this is a static clone
- The SSL certificate issue from the original hosting provider has been resolved by moving to a new host

## Original Site

Original site: https://john-charles.com/
Cloned on: January 4, 2026
