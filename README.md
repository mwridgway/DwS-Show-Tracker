# DwS Show Tracker

Phone-friendly running order for the DwS Studio Showcase 2026, with a live "on stage now" tracker.

- `index.html` is the whole site. Every phone checks `state.json` every 10 seconds.
- To run the tracker, open the site with `#owner` at the end of the link, open Filter, and paste a fine-grained GitHub token with **Contents: Read and write** on this repo. Taps then commit `state.json`, and the site redeploys automatically.
