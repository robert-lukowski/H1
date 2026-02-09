# H1 2025 Team Impact Dashboard

A polished, single-page portfolio-style web experience presenting first-half 2025 achievements for the Service Desk team.

The project combines storytelling, visual highlights, and quick navigation to showcase:
- customer feedback,
- operational progress,
- automation initiatives,
- training and certification results,
- and personal/team development milestones.

## Project Highlights

- **Immersive landing experience** with intro overlay and video background.
- **Interactive feedback carousel** with multiple testimonials.
- **Animated KPI section** for ticket-resolution progress.
- **Project showcase cards** linking to dedicated subpages:
  - Next Action Tool,
  - QuickShare App,
  - Training & shadowing,
  - Growth & certifications.
- **Built-in mini assistant widget** with quick predefined prompts.
- **Rich media support** (images, MP4 demos, PDF certificates).

## Tech Stack

- **HTML5** for page structure.
- **CSS3** for styling, transitions, and layout.
- **Vanilla JavaScript** for interactivity and UI behavior.
- **Static assets** (images, videos, PDF) served directly.

## Repository Structure

```text
.
├── index.html              # Main dashboard page
├── main.js                 # Core interactions and animations
├── chatbot.js              # Assistant widget logic/content
├── style.css               # Main styling
├── login.html              # Login entry view
├── login-style.css         # Login view styles
├── next-action.html        # Next Action Tool page
├── quickshare.html         # QuickShare project page
├── szkolenia.html          # Training/shadowing page
├── rozwoj.html             # Growth/certifications page
├── images/                 # Feedback and branding visuals
├── video/                  # Background and demo videos
└── certyfikaty/            # Certification documents (PDF)
```

## Getting Started

Because this is a static website, no build step is required.

### Option 1: Open directly
Open `index.html` in your browser.

### Option 2 (recommended): Run a local server
Using Python:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Editing & Customization

To adapt this dashboard for a different reporting cycle or team:

1. **Update narrative/content** in `index.html` and subpages.
2. **Replace media assets** in `images/`, `video/`, and `certyfikaty/`.
3. **Adjust progress metrics** in `main.js` (`animateProgressBar(...)`).
4. **Modify assistant responses** in `chatbot.js`.
5. **Tune look & feel** in `style.css` and `login-style.css`.

## Deployment

This project can be deployed to any static hosting provider, for example:
- GitHub Pages,
- Netlify,
- Vercel (static output),
- or internal company web servers.

## Notes

- The current UI copy is mainly in Polish.
- The README is intentionally in English to support wider collaboration.

## License

No license file is currently defined in this repository.
If you plan to share this publicly, add a `LICENSE` file (e.g., MIT, Apache-2.0, or proprietary internal license).
