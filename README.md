# amora-cron

Pinger for [Amora Mail](https://amora-mail.vercel.app): hits the background poll
endpoint every ~5 minutes so incoming email is fetched and automatic AI replies
are generated/sent even when nobody has the app open.

The endpoint is protected by a secret (`CRON_SECRET`, stored as a GitHub Actions
secret here and as a Vercel env var there). This repo contains no credentials.

<!-- ping amora-mail.vercel.app -->
