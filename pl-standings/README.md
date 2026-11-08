# Premier League 2025/26 – Table and results

Static website (one `index.html`, no build step) showing the final league table,
the results of every matchweek, and a page per club with all its matches.
Standings are calculated in the browser from the 380 results
(win 3, draw 1, loss 0; ranked by points, goal difference, goals scored).

Author: Adam Ahmad Moussa (116589) – I3306 Database 2 project.

## Deploy on Vercel

Option A – GitHub (no installs):
1. Create a new GitHub repository and upload these files (index.html, vercel.json, README.md).
2. On vercel.com, choose "Add New… > Project", import the repository.
3. Framework preset: "Other". Leave build settings empty. Click Deploy.

Option B – command line (needs Node.js):
    cd pl-standings
    npx vercel          # first time: log in and accept the defaults
    npx vercel --prod   # publishes the production URL
