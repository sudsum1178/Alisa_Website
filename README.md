# AlisaSite — starter

Place Alisa's PNG files into the `images/` folder and push to GitHub.

Steps to add your two PNGs and publish:

1. Copy your PNG files into `AlisaSite/images/` and rename them to:
   - `alisa-photo-1.png`
   - `alisa-photo-2.png`

2. From PowerShell in the `AlisaSite` folder run:

```powershell
git init
git add .
git commit -m "Initial site with images"
# create repo on GitHub via web or with gh CLI, then:
git remote add origin https://github.com/yourusername/alisa-site.git
git branch -M main
git push -u origin main
```

3. (Optional) Add a CNAME file or set the custom domain under the repo Settings → Pages when ready to point your GoDaddy domain.
