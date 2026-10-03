# Pranjal Raj Portfolio

Single-file static portfolio (`index.html`). No build step.

## Deploy
- **Vercel / Netlify:** import the GitHub repo, framework "Other", no build command, output directory `/`.
- **GitHub Pages:** Settings > Pages > Deploy from branch > `main` / root.

## Push to GitHub
```
git init
git add .
git commit -m "Add portfolio"
git branch -M main
git remote add origin https://github.com/PranjalRajputt/<repo-name>.git
git push -u origin main
```

## Note on the chat assistant
The "Let's talk" chat uses Claude only inside claude.ai. On your own domain it automatically uses built-in answers about your projects, skills and contact details. To get AI replies on your own site, connect the chat to a backend API route (e.g. a Vercel serverless function) that calls an LLM API.
