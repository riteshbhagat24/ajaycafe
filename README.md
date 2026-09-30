# Ajay's Cafe — Interactive Video Learning POC

A mobile-first interactive video lesson built as a static HTML/CSS/JS prototype for an LMS demo.

## Files
- `index.html` — complete application
- `videoplayback.mp4` — actual lesson video

## Demo interaction
- 4 questions appear at relevant points during the 4:48 video.
- The video pauses when a checkpoint is reached.
- The learner selects an answer and clicks **Record answer**.
- The question disappears immediately and the video resumes.
- Answers are scored only after the video finishes.
- The final screen shows the percentage and question-by-question review.

## Questions
1. Purpose of “Are you ready to order?” — 00:39
2. Main course ordered — 01:11
3. Drink requested at the counter — 02:58
4. Frequency of eating this type of food — 04:16

## Run locally
Open `index.html` through a local web server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy on Vercel via GitHub
1. Create a GitHub repository.
2. Upload `index.html`, `videoplayback.mp4`, and `README.md` to the repository root.
3. Import the repository into Vercel.
4. Framework Preset: **Other**.
5. Build Command: leave blank.
6. Output Directory: leave blank.
7. Deploy.

Keep the video and HTML in the same directory.
