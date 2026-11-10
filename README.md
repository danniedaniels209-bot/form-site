# FORM — Sound for Every Move

> Independent wireless earbuds design concept by **EVOLVZ**.

A single-page, full-screen concept site featuring dynamic video backgrounds, frosted-glass UI layers, kinetic SVG typography, interactive magnetic pills, 3D tilt cards, and adaptive orientation handling.

---

## ✨ Features

- **Full-Screen Video Sections**: Ambient video sections with seamless transitions and staged decoding.
- **Frosted Glass UI**: Custom glassmorphic navigation bar, pill buttons, and overlay controls.
- **Fluid Layout**: Responsive typography and spatial scaling using dynamic CSS viewport units (`--vw`, `--vh`).
- **Rotated Phone Layout**: Intelligent portrait-to-landscape layout transformation for upright phone screens (`body.rot`).
- **Self-Contained**: Embedded base64 video clips decoded directly on boot into Object URLs.
- **Custom Cursor & Magnetic Interactions**: Physics-based cursor trailing, magnetic button attraction, and perspective tilt on interactive cards.

---

## 🚀 Getting Started

Simply open `index.html` in any modern web browser, or serve it locally:

```bash
# Using Python
python -m http.server 8080

# Or using Node.js npx
npx serve .
```

Then visit [http://localhost:8080](http://localhost:8080).

---

## 🌐 Deploy to Render

A [`render.yaml`](render.yaml) Blueprint is included for zero-config static site deployment:

1. Go to the [Render Dashboard](https://dashboard.render.com/).
2. Click **New +** > **Blueprint**.
3. Connect your repository `danniedaniels209-bot/form-site`.
4. Render will detect `render.yaml` and deploy the static site automatically.

---

## 📱 Mobile Experience

On phones held upright, the layout rotates 90° for an immersive cinematic wide-aspect experience. Simply rotate your phone to landscape or view naturally with auto-rotate.

---

*Independent design concept. Product imagery and video assets are illustrative.*
