# North 40 Safety Tools

Static mobile-friendly safety tools dashboard for GitHub Pages.

## Included Tools

- Monthly Safety Audit
- Safety Meeting Minutes PDF Export

## Folder Structure

```text
/
├── index.html
├── audit/
│   └── index.html
├── meeting-minutes/
│   └── index.html
├── logo.png
├── icon-180.png
├── icon-192.png
├── icon-512.png
├── manifest.webmanifest
└── .nojekyll
```

## Deploy with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files and folders from this package into the repository.
3. Go to **Settings**.
4. Go to **Pages**.
5. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/ root**
6. Click **Save**.
7. GitHub will publish the site after a minute or two.

Your app URL will look like:

```text
https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/
```

## iPhone Home Screen

Open the GitHub Pages URL in Safari, then:

```text
Share → Add to Home Screen
```

The custom icon metadata is already included.
