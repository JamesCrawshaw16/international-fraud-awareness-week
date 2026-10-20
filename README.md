# Paths to Fraud

Mobile-first workplace fraud-awareness simulation.

## Routes
- `/tickets`
- `/deepfake`
- `/events`
- `/bins`
- `/cafe` — Cafe One menu, Leeds Office, floor 6

## Deploy
Import this repository into Vercel (Framework Preset: Other). Route rewrites are in `vercel.json`.

## Privacy and counter
Email is parsed only in the browser to personalise the reveal, then cleared. The counter API receives only the campaign key, never the email or name. Anonymous completion events increment `ifa:reveals:total` and `ifa:reveals:<campaign>` in Redis. Counts represent completions, not unique employees. Configure `KV_REST_API_URL` and `KV_REST_API_TOKEN` (or the corresponding `UPSTASH_REDIS_REST_*` variables) on Vercel.
