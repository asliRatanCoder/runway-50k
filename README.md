# Runway to ₹50K

Personal tracker for the outbound freelance goal: daily outreach counters, lead pipeline, income ledger, and the funnel math from cold emails to ₹50,000 a month.

Single static page (`index.html`), no build step. Served by GitHub Pages.

**Data** is never stored in this repo. The page keeps a cache in the browser and, once connected in Settings, commits every change to the private repo `runway-50k-data` (file `data.json`) using a fine-grained token that can only touch that repo. Export/Import JSON is available as a manual backup.
