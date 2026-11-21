# Landing digiskill.ai

Static site for https://digiskill.ai, including the BYAT program page at `/byat/build-your-first-agent-team`
(three tiers: $80 live only, $100 community + 6-month recordings, $300 group of 5; each button goes to a Stripe Payment Link).

- Source recovered from production deployment `dpl_FvdvJ7hTFRb1G83yTABjB71yH6mc`, then `/byat/` added.
- Vercel project: `digiskill-ai` in the Ambysto team (steady-wealth). Deploy from this folder with the Ambysto Vercel login:
  `vercel link --yes --scope steady-wealth --project digiskill-ai` once, then `vercel deploy --prod --yes`.
- `.github/workflows/deploy.yml` belongs to the original landing repo; it does not run from this subfolder.
- No secrets live here. The Stripe key stays in a local `.env.local`, never committed.
