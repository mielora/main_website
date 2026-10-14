# Publish MIELORA with GitHub Pages

1. Create a new public GitHub repository, for example `mielora-website`.
2. Extract this ZIP file.
3. Upload every extracted file and folder directly to the repository root. `index.html` must remain at the root.
4. Open the repository's **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the `/(root)` folder, then click **Save**.
7. Wait a few minutes for GitHub to display the live website URL.

The website itself has not been visually modified for this package. The `.nojekyll` file is included for predictable static-file publishing.

When a final custom domain or GitHub Pages URL is chosen, update the canonical URL, Open Graph URL/image URLs, `robots.txt`, and `sitemap.xml` for correct SEO indexing.
