# NEXUS AI SaaS Platform

Static frontend prototype for an AI workspace with landing page, dashboard, AI chat, billing, usage metrics, and command palette navigation.

## Run locally

Open `index.html` in a browser. No build step or Node.js is required.

## Deploy with GitHub Pages

1. Open the repository `Settings` -> `Pages`.
2. Under `Build and deployment`, set `Source` to `GitHub Actions` and save.
3. Open the `Actions` tab and run `Deploy NEXUS to GitHub Pages` with `Run workflow`, or push another commit.
4. Open the generated Pages URL from the workflow's `Deploy` step.

The Pages setting must be enabled once by a repository administrator. Until it is enabled, `actions/configure-pages` returns `404 Not Found` and the deployment cannot start.

The current AI chat is a frontend demo. Chat history is stored in the browser's local storage. Real AI, authentication, uploads, billing, and database features require a backend.
