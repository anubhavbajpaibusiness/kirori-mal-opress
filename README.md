# Kirori Mal College Voicebox

Anonymous complaint & suggestion box for the Kirori Mal College Students'
Union. Static frontend in `public/`, three serverless API routes in `api/`,
shared auth helper in `lib/`, and data stored in Upstash Redis.

It is designed to coexist safely on the **same Upstash Redis database** as
the Aditi Mahavidyalaya Voicebox deployment — every key it writes is
namespaced under `du:kmc:voicebox`.

---

## Deploy in 5 minutes

### 1. Push to GitHub
```bash
git init
git add .
git commit -m "kmc-voicebox"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main