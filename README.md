run on local
```
npm run dev
```

push and deploy on GitHub: normal GH push. GitHub Actions are already set to automatically run `.github/workflows/deploy.yml`.
```
git add . && git commit -m "update" && git push origin main
```
