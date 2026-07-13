# Ariel O. Saracho — Academic Website

A responsive static academic website designed for GitHub Pages.

## Publish on GitHub Pages

1. Create a GitHub repository named `YOUR-USERNAME.github.io`.
2. Upload all files in this folder to the repository root.
3. Commit and push the files.
4. In GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select the `main` branch and `/ (root)` folder.
7. The site will appear at `https://YOUR-USERNAME.github.io`.

## Before publishing

Edit `index.html` and replace the placeholder Google Scholar and LinkedIn links with your real profile URLs.

To use a portrait:

1. Add an image such as `assets/profile.jpg`.
2. Replace this element:

```html
<div class="portrait-placeholder" aria-hidden="true">AS</div>
```

with:

```html
<img class="profile-photo" src="assets/profile.jpg" alt="Portrait of Ariel O. Saracho" />
```

Then add this CSS to `styles.css`:

```css
.profile-photo {
  width: 120px;
  height: 120px;
  object-fit: cover;
  border-radius: 50%;
  margin-bottom: 24px;
}
```

## Updating the CV

Replace `assets/Ariel_Saracho_CV.pdf` with the latest version while keeping the same filename.
