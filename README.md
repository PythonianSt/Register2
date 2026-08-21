# KU Registration Queue — Vercel prototype (fixed root layout)

Deploy this folder as the ROOT of the GitHub repository / Vercel project.

Routes:
- `/` mobile registration
- `/records` medical-records dashboard
- `/triage` triage dashboard

Important: In Vercel > Project > Settings > Build and Deployment, leave Framework Preset as Other and ensure Root Directory points to the folder containing `vercel.json` and `index.html` (normally `./`).

Add environment variables from `.env.example`, then redeploy.
