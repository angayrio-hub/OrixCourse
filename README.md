# YouTube Automation Mastery — Phase 1 Free Course

A fully self-contained HTML course page. No build steps, no dependencies, no server required.

## 🚀 Deploy to GitHub Pages (3 steps)

1. **Create a new GitHub repository** (e.g. `yt-auto-course`)
2. **Upload `index.html`** to the root of the repo
3. Go to **Settings → Pages → Source → Deploy from main branch / root**

Your course will be live at:
```
https://OrixCourse.github.io/yt-auto-course/
```

## 📁 File Structure

```
/
└── index.html   ← The entire course (single file, no dependencies)
```

## ✏️ Customizing Content

Everything is in `index.html`. Search for these sections to edit:

| What to change | Search for |
|---|---|
| Course title / branding | `YT AUTO` |
| Hero headline | `<h1>` in hero section |
| Stats (lessons, phases) | `hero-stats` section |
| Module list | `modules-list` |
| Niche cards + CPMs | `niches-grid` |
| Tools | `tools-grid` |
| Roadmap phases | `roadmap` section |
| CTA features list | `cta-features` |

## 🎥 Linking Real Videos

Replace the video placeholder click handler with a real YouTube embed URL:

```html
<!-- Find this in index.html and replace the YouTube URL: -->
src='https://www.youtube.com/embed/YOUR_VIDEO_ID?autoplay=1'
```

## 🎨 Changing Colors

Edit the CSS variables at the top of the `<style>` block:

```css
:root {
  --accent: #e8ff47;   /* yellow-green highlight color */
  --accent2: #ff4747;  /* red accent */
  --bg: #0a0a0b;       /* page background */
  --text: #f0f0f5;     /* body text */
}
```

## 📝 Phases 2–5

When you're ready to add more phases, duplicate `index.html` as:
- `phase-2.html`
- `phase-3.html`
- etc.

Then link them from the modules list by updating the `href` on locked module items.

---

Built with vanilla HTML/CSS/JS — zero frameworks, zero build tools, runs anywhere.
