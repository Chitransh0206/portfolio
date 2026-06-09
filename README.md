# Portfolio Deployment

This folder contains a static portfolio website centered around `index.html`.

## Use the correct folder

From PowerShell, run:

```powershell
cd E:\portfolio_final
```

There is no `portfolio` subfolder in this workspace.

## Deploy options

### GitHub Pages

1. Initialize git and commit:
   ```powershell
git init
ngit add .
git commit -m "Initial portfolio deploy"
```
2. Add your remote and push:
   ```powershell
git branch -M main
git remote add origin https://github.com/<your-user>/<your-repo>.git
git push -u origin main
```
3. In GitHub repository settings, enable Pages from branch `main` and folder `root`.

### Netlify / Vercel

- Connect your GitHub repository to Netlify/Vercel.
- Use the root folder as the publish directory.
- No build command is required for this static site.
