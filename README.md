# Mrs Kitchen Website

A static website for GitHub Pages. No build tools or installation required.

## Easiest way to publish with GitHub Pages

1. Download `Mrs_Kitchen_GitHub_Upload.zip` and extract it on your computer.
2. Sign in at https://github.com and click **New repository**.
3. Name the repository `mrs-kitchen-website` (or another name you prefer), set it to **Public**, then click **Create repository**.
4. In the new repository, click **Add file → Upload files**.
5. Open the extracted folder on your computer and select the website files and the `images` folder. Upload the *contents* of the folder so `index.html` appears at the top level of the repository—not inside another folder.
   - Required top-level files: `index.html`, `styles.css`, `products.js`, `script.js`, `README.md` and `README.txt`.
   - Also upload the complete `images` folder.
6. Wait for the upload to finish, enter a commit message such as `Upload Mrs Kitchen website`, and click **Commit changes**.
7. In the repository, open **Settings → Pages**.
8. Under **Build and deployment**, set **Source** to **Deploy from a branch**. Choose branch **main** and folder **/(root)**, then click **Save**.
9. Wait a minute or two. Refresh **Settings → Pages**; GitHub will show your published website link there.

## Important checks

- The `index.html` file must be in the repository root, alongside `styles.css`, `products.js` and `script.js`.
- Keep all product photos in the `images` folder. Do not rename it.
- The website is static HTML/CSS/JavaScript, so GitHub Pages can host it for free without a build step.
- Product prices are set to “Price on request” because confirmed prices were not provided. Edit `products.js` to add accurate prices (in rand) and verified product details.
- Check the address and product descriptions before publishing publicly.
- WhatsApp ordering uses `https://wa.me/27710331241`.
