# Four Paths to Fraud

Static, mobile-first workplace fraud-awareness simulation.

## Routes
- `/tickets`
- `/deepfake`
- `/events`
- `/bins`

## Deploy
Upload the folder to a GitHub repository and import it as a Vercel project (Framework Preset: Other; root directory: repository root). The `vercel.json` rewrites make each route work on refresh.

## Privacy
The submitted email is parsed entirely in the browser to extract a first name; no network request, analytics, or storage is implemented. No shared counter is implemented yet. The app is explicitly labelled an authorised awareness simulation.
