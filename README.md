# Spidey Gym

Jacob's phone workout app: a 4-day upper/lower beginner split with an abs finisher every day, built for Onelife Fitness.

- Live: https://canadyjacob14-collab.github.io/spidey-gym/
- Mirror: https://jacob-spidey-workout-3u2x.deed.page/

It's a single static `index.html` with no build step. Logs are saved in the browser's localStorage, and Settings has JSON export and import. Exercise photos come from [free-exercise-db](https://github.com/yuhonas/free-exercise-db) (Unlicense / public domain).

Pushing to `main` deploys through `.github/workflows/pages.yml`. Settings → Pages → Source must be set to **GitHub Actions**.
