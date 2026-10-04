# Roottoo Connect CRM — UI Starter

A responsive, animated CRM dashboard concept for Roottoo Innovation covering Accounting & Taxation, Staffing, and Managed Services.

## Included

- Premium responsive dashboard UI
- Animated Three.js orbital visual for three service lines
- Navigation, live activity feed, metrics, workflow cards, global search mock-up
- AI Copilot modal mock-up
- Vite build configuration and Netlify deployment configuration

## Run locally

```bash
npm install
npm run dev
```

Open the local address printed by Vite.

## Build

```bash
npm run build
npm run preview
```

## Deploy to Netlify

1. Create a GitHub/GitLab/Bitbucket repository and upload these files.
2. In Netlify, select **Add new project** and import the repository.
3. Netlify uses the included settings automatically:
   - Build command: `npm run build`
   - Publish directory: `dist`
   - Node version: `20`
4. Add application secrets only through Netlify environment variables; never add them to source code.
5. Deploy and attach a custom domain, such as `crm.roottooinnovation.com`.

## Important production work still required

This download is a polished frontend starter—not a finished production CRM. Add the following before handling real client data:

- Secure authentication and role-based authorization
- PostgreSQL database and encrypted document storage
- API/serverless functions
- Accounting, staffing, managed-services data models and workflows
- Audit logs, backups, rate limiting, validation, monitoring, and security reviews
- AI provider integration with access controls, human approval, and prompt/audit logging

## Suggested next stack

- Frontend: React + Vite (included) or migrate to Next.js
- Hosting: Netlify
- Database/Auth: Supabase or PostgreSQL plus a dedicated auth provider
- Storage: Supabase Storage or S3-compatible storage
- AI: a secure server-side LLM integration; never expose provider keys in browser code
