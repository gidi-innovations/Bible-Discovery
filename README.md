# Bible Discovery: Life in Christ

A mobile-first, self-discovery Bible study web app. Made by Gemma Pyne-Bailey.

People choose their starting point (exploring Jesus, new to following Jesus, growing and training others, or coming back after drifting) and work through 3/3 Discovery Bible Study lessons: Look back, Look up, Look forward.

## What's inside

- `index.html` - the whole app (HTML, CSS and JavaScript in one file)
- `data/series.json` - all courses and lessons
- `data/kjv.json`, `data/bbe.json`, `data/web.json` - full Bibles: King James Version, Bible in Basic English, World English Bible
- `data/lex.json` - Strong's Hebrew and Greek dictionary (Word search tool)
- `data/hand.json` - The Gospel on the Hand tool

## Put it online with GitHub Pages

1. Create a new repository on GitHub (for example `bible-discovery`).
2. Upload everything in this folder, keeping the `data` folder as it is.
3. Go to **Settings > Pages**, choose **Deploy from a branch**, pick `main` and `/ (root)`, and save.
4. After a minute or two your app is live at `https://YOUR-USERNAME.github.io/bible-discovery/`.

To test on your own computer, run a small local server in this folder (for example `python3 -m http.server`) and open `http://localhost:8000`. Opening `index.html` directly from your files will not load the data.

## Notes

- Progress, notes and prayers are saved in each person's browser on their own device.
- The **Ask** and **Share with my guide** features use Claude and only work inside claude.ai. On GitHub Pages they hide themselves automatically; everything else works.
- Scripture: KJV, BBE and WEB are public domain. NIV, The Message and ERV are linked on BibleGateway, not included.
- Strong's Concordance data from Open Scriptures (CC BY-SA). The Gospel on the Hand from AIM Trainers (aimtrainers.org).
