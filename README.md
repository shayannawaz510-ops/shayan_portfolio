# Shayan (Portfolio)

Project structure and quick start

Project layout:

- `index.html` — main page (references assets in `css/`, `js/`, and `images/`).
- `css/styles.css` — main stylesheet (Tailwind is used for utilities).
- `js/head.js` — Tailwind configuration.
- `js/main.js` — main JavaScript (animations, contact form handler).
- `images/` — project images / placeholders.

Run locally:

1. Open `index.html` in a browser directly, or run a simple static server for fuller compatibility:

   Python 3:

   ```bash
   python -m http.server 8000
   ```

   Then open http://localhost:8000 in your browser.

Contact form:

- The contact form opens the user's mail client using a `mailto:` fallback, sending to the email shown on the page.
- To enable automatic delivery without a mail client, integrate a service such as EmailJS or Formspree and add the service ID in `js/main.js` (example commented there).

If you'd like, I can:

- Integrate EmailJS with your account details so the form sends automatically.
- Add build scripts or package.json if you want a Node-based dev server.
