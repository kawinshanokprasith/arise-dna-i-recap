# Inside DNA-i

Photos, videos and notes from ARISE Tech Meetup 12 · DNA-i (7 Nov 2026, The PARQ), in the order they were shot.
Every caption is in English and Thai. Photos and videos zoom (scroll or pinch, drag to pan, double-click).

This is the **high-quality** build: photos at 3200 px, videos at 1080p (about 5 Mbps) so on-screen text stays readable.

## Run it on your computer

```bash
cd arise-dna-i-recap-github
python3 -m http.server 8000
```

Then open http://localhost:8000. (Opening `index.html` straight from Finder also works, but a local server is more reliable.)

## Put it on GitHub Pages

1. Push this folder to a GitHub repository.
2. In the repository, open Settings > Pages, choose "Deploy from a branch", branch `main`, folder `/ (root)`.
3. The site appears at `https://<username>.github.io/<repository>/`.

The whole site must stay under 1 GB and no single file over 100 MB (GitHub's limits). Videos longer than about 90 seconds are already split into parts that play back to back.

## Files

- `index.html` is the page, `data.js` holds every section, caption and the front pages (edit captions there).
- `media/photos`, `media/thumbs`, `media/videos`, `media/posters` are the pictures and clips.
- `media/owl` is the animated owl from the Owloo design system, `fonts/` is the Owloo heading font.

## Before you make the repository public

- **People:** the exhibition photos show attendees' faces. A private repository (with Pages for private repos on a paid plan) or sharing only inside your team is safer.
- **Fonts:** `fonts/kondolar-*.otf` come from the Owloo design system. Check the font's licence before publishing them publicly. If it is not allowed, delete the folder; the page falls back to Chakra Petch.
- **Client content:** the talks are from a public event, but check nothing here is client material.
