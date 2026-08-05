# Field-Fox Landing Page

A responsive static landing page built with HTML, CSS, and a small amount of JavaScript.

## Files

- `index.html` — page content
- `styles.css` — responsive styling
- `script.js` — mobile navigation and automatic copyright year

## Customize before deploying

1. Replace `hello@field-fox.com` in `index.html` with your real email address.
2. Adjust the page copy to match the exact Field-Fox product.
3. Add analytics or a form provider if needed.

## Deploy with Cloudflare Pages

### Option 1: Direct Upload

1. Sign in to Cloudflare.
2. Open **Workers & Pages**.
3. Select **Create application** → **Pages** → **Upload assets**.
4. Upload this folder or the included ZIP file.
5. After deployment, open the project's **Custom domains** section.
6. Add your domain or subdomain.

No build command is required because this is a static website.

### Option 2: GitHub

1. Create a GitHub repository.
2. Add these files to the repository.
3. In Cloudflare Pages, choose **Connect to Git**.
4. Select the repository.
5. Leave the build command blank.
6. Set the output directory to `/` or leave it blank, depending on the Cloudflare interface.
7. Deploy and attach your custom domain.
