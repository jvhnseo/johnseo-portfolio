# John Seo — Final Web Dev Project

A creator-brand personal site for IS 110 final project.

## What's here

| File | What it is |
|---|---|
| `index.html` | Bootstrap landing page (pro site) |
| `about.html` | Bootstrap about page |
| `resume.html` | Bootstrap HTML resume |
| `scratch.html` | From-scratch page (no Bootstrap) — Field Notes lab |
| `app.html` | AI-powered street interview question generator |
| `css/bootstrap-custom.css` | Custom CSS #1 (for Bootstrap pages) |
| `css/scratch.css` | Custom CSS #2 (for scratch page) |
| `images/mic-portrait.svg` | Custom SVG image used on scratch page |

## Requirement checklist

### From-scratch page (`scratch.html`)
- ✅ Made from blank HTML, no Bootstrap
- ✅ Unordered list nested inside an ordered list (see "The rulebook")
- ✅ Image not from Bootstrap theme (`images/mic-portrait.svg`)
- ✅ Embedded YouTube video (iframe)
- ✅ On-page anchors (jump menu + back-to-top)
- ✅ Custom background (dark paper + radial gradients + subtle scanlines)
- ✅ Links to own stylesheet (`css/scratch.css`) with:
  - 4+ style definitions (dozens here)
  - Font color (`color: #ff5a1f`, `#f4efe6`, etc.)
  - Font family (`Georgia`, `Courier New`)
- ✅ 3+ divs for positioning (`.wrap`, `.intro`, `.rule-block`, `.video-frame`, `.tableau-frame`, etc.)
- ✅ Live Tableau embed (Superstore public viz — interactive, not an image)
- ✅ Navigation back to Bootstrap pages (top bar)
- ✅ Links to the web app page

### Web app (`app.html`)
- ✅ Single-page — all HTML, CSS, JS in one file
- ✅ Built with AI collaboration (Claude API integration)
- ✅ Creative contribution beyond a basic template: custom design system, vibe + topic controls, save/copy/regenerate functionality, session log
- ✅ Linked from scratch page

### Resume
- ✅ HTML (not PDF) — on `resume.html`
- ✅ Education, work experience, skills, notable items

## Hosting on GitHub Pages

1. Create a new public repo on GitHub (e.g., `johnseo-portfolio`).
2. Upload all these files preserving folder structure:
   ```
   /
   ├── index.html
   ├── about.html
   ├── resume.html
   ├── scratch.html
   ├── app.html
   ├── css/
   │   ├── bootstrap-custom.css
   │   └── scratch.css
   └── images/
       └── mic-portrait.svg
   ```
3. Go to **Settings → Pages**.
4. Under **Source**, select **Deploy from a branch**.
5. Pick `main` branch, `/ (root)` folder, and Save.
6. Wait ~1 minute. Your site will be live at:
   `https://<your-username>.github.io/<repo-name>/`

## URLs to submit

- **Pro site**: `https://<your-username>.github.io/<repo-name>/index.html`
- **Scratch page**: `https://<your-username>.github.io/<repo-name>/scratch.html`
- **Web app**: `https://<your-username>.github.io/<repo-name>/app.html`

## Things to swap before submitting

- Social links on `index.html` currently point to placeholder handles — update `@jvhnseo` to your actual handles.
- YouTube embed on `scratch.html` uses a classic reference video — swap the video ID in the iframe `src` if you want to use one of your own clips. Find your ID in any YouTube URL: `youtube.com/watch?v=VIDEO_ID_HERE` → then use `https://www.youtube.com/embed/VIDEO_ID_HERE`.
- The resume stats (2.4M monthly reach, etc.) are placeholders — adjust to your real numbers.
