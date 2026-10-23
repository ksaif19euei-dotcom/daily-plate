# Daily Plate PWA — GitHub Pages

## Publish with GitHub Pages

1. Create a GitHub repository for the app.
2. Upload the contents of this folder to the repository root (so `index.html` is at the top level), then commit the files to the `main` branch.
3. In the repository, open **Settings → Pages**. Under **Build and deployment**, choose **Deploy from a branch**, select **main** and **/(root)**, then save.
4. Wait for the Pages deployment to finish. Open the `https://<your-account>.github.io/<repository>/` address on your phone.
5. On Android/Chrome, tap **Install app** when it appears, or choose it from the browser menu. On iPhone/Safari, use **Share → Add to Home Screen**.

The service worker and manifest use relative paths, so this works from a GitHub Pages project URL as well as a domain root. Meal entries and photos stay in that browser on that device; they are not synced between devices. Offline support begins after the first visit.
