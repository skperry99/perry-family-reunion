# Perry Family Reunion 2026 – St. Louis, MO

A simple, static website for the **1st Perry Family Reunion** in the St. Louis / O’Fallon, Missouri area, celebrating the descendants of **William Henry Perry Sr.** and **Irene “Irja” Marie (Hakala) Perry**.

The site is meant to be warm, easy to read, and shareable with family members of all ages. It includes general information, a high-level family tree snapshot, travel details, and links to RSVP via Google Forms.

---

## Live Site

- GitHub Pages: `https://skperry99.github.io/perry-family-reunion/index.html`

---

## Features

- **Multi-page layout** using plain HTML + CSS (no frameworks required)
- **Responsive design** that works on desktop, tablet, and mobile
- **Sticky navigation bar** with a clear “RSVP” call-to-action
- **Family-focused content**, including:
  - Our Story & family roots in Cornwall, Finland, and Michigan’s Upper Peninsula
  - A **Family Tree Snapshot** showing founders, their children, and generations today
  - A **Reunion Weekend** overview (Friday–Sunday)
  - **Travel & Lodging** information near O’Fallon, MO
  - **Family Memories** page inviting stories and reconnection
  - **In Loving Memory** section honoring William & Irene and their children
  - **RSVP page** with an embedded Google Form and organizer contact info

---

## Tech Stack

- **HTML5**
- **CSS3**
- No JavaScript frameworks (only a small script for the mobile nav toggle)

This makes the site easy to host on GitHub Pages, Netlify, or any static file host.

---

## Project Structure

```text
.
├── index.html          # Home page with hero and quick links to other pages
├── our-story.html      # Family origin story + high-level family tree snapshot
├── weekend.html        # Reunion weekend overview + Celebration of Life note
├── travel.html         # Travel & lodging info near O’Fallon, MO
├── memories.html       # Invitation to share memories & stories
├── in-memory.html      # In Loving Memory page for William, Irene, and their children
├── rsvp.html           # RSVP page with Google Form embed and contact info
└── styles.css          # Shared styles for all pages (layout, colors, components)
````

---

## Running the Site Locally

You don’t need any special tools to view the site — just a browser.

1. Clone the repository:

   ```bash
   git clone https://github.com/<username>/perry-family-reunion.git
   cd perry-family-reunion
   ```

2. Open `index.html` in your browser:

   * Double-click `index.html`, **or**
   * Right-click → “Open With” → your preferred browser.

For local development with live reload, you can optionally use a simple static server (e.g. VS Code Live Server, `python -m http.server`, etc.).

---

## Deployment

### GitHub Pages

1. Push the project to a GitHub repository (e.g. `perry-family-reunion`).
2. In the repo settings, enable **GitHub Pages**:

   * Source: `main` branch
   * Folder: `/root` (or `/docs` if you move files there)
3. GitHub will provide a public URL like:

   ```text
   https://<username>.github.io/perry-family-reunion/
   ```

### Netlify (optional)

1. Create a Netlify account.
2. Click **“New site from Git”**.
3. Connect your GitHub repo.
4. Build command: *none*
   Publish directory: `/`
5. Deploy — Netlify will give you a URL you can share with family.

---

## Customization

Most edits can be made by adjusting:

* **Text & content**:

  * Edit the relevant `.html` file (e.g. `our-story.html`, `weekend.html`, `in-memory.html`).
* **Colors, spacing, and components**:

  * Edit `styles.css`.
  * Key theme variables are in the `:root` section:

    * Backgrounds, text colors
    * Accent colors (deep green + warm rust)
    * Card radius, shadows, spacing scale

If family members spot details that should be updated (names, dates, locations), they can contact the organizer, and those changes can be made directly in the HTML.

---

## Credits

* Content and organization: **Sarah Perry**
* Family history and stories: Descendants of William & Irene Perry
* RSVP & coordination: via Google Forms and email

> From Cornwall & Finland to the Upper Peninsula, to St. Louis and beyond.
