# html-to-pages

A simple repository that automatically publishes `index.html` to GitHub Pages.

## How it works

1. Edit the `index.html` file in the repository root
2. Commit and push your changes to the `main` branch
3. GitHub Actions will automatically deploy the updated page to GitHub Pages

## Setup

To enable GitHub Pages for this repository:

1. Go to the repository **Settings**
2. Navigate to **Pages** in the sidebar
3. Under **Source**, select **GitHub Actions**
4. The workflow will automatically deploy on every push to the `main` branch

## Manual Deployment

You can also manually trigger the deployment from the **Actions** tab by selecting the "Deploy to GitHub Pages" workflow and clicking "Run workflow".

## Viewing Your Site

Once deployed, your site will be available at:
```
https://<username>.github.io/html-to-pages/
```

Replace `<username>` with your GitHub username or organization name.