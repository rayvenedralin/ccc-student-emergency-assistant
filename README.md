# CCC Student Emergency Assistant 🚨
### Mobile Web Application Prototype for Higher-Education Campus Safety

A responsive, browser-based mobile web application prototype designed for **City College Central (CCC)** students, faculty, and campus security dispatch. Built with high-contrast emergency triage ergonomics, modern institutional design, and zero dependencies.

---

## 🚀 Live Demo & GitHub Pages Deployment

This application is ready to deploy directly to **GitHub Pages (`github.io`)**.

### How to Deploy to GitHub Pages in 3 Steps:

1. **Push this repository to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: CCC Student Emergency Assistant"
   git branch -M main
   git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**:
   - Go to your repository on GitHub.
   - Click **Settings** (tab at the top).
   - In the left sidebar, click **Pages**.
   - Under **Build and deployment > Source**, select **Deploy from a branch**.
   - Under **Branch**, select `main` and folder `/ (root)`.
   - Click **Save**.

3. **Access Your Live Web App**:
   - Your site will be live at:  
     `https://<YOUR-USERNAME>.github.io/<YOUR-REPO-NAME>/`

---

## 📱 Features

- **Device Simulator & Responsive Engine**: Centered iPhone 15 Pro frame with notch, live clock, and titanium chassis on desktop; seamlessly stretches to 100% native mobile viewport on phones.
- **Screen 1: Sign-In Gateway**: Pre-filled student credentials, attempt counter, identity verification, and 1-tap SOS emergency bypass.
- **Screen 2: Home Safety Dashboard**: Real-time campus safety status pulse (Code Green Normal), urgent crimson SOS banner, 2x2 quick triage grid, campus bulletins, and persistent bottom tab bar.
- **Screen 3: Emergency Dispatch (SOS)**: Live GPS telemetry fix (±3m), category selectors, indoor triangulation radar, and a 2-second hold-to-confirm radial progress SOS button with dispatch modal and live ETA.
- **Screen 4: Report a Campus Issue**: Dynamic category chips, quick location auto-pins, description counter, photo evidence upload preview, and instant submission to the live tracker.
- **Screen 5: Campus Services Directory**: Real-time search filter across offices, duty extensions, operating hours, category filter chips, and interactive VoIP call simulator.
- **Screen 6: My Requests Tracker**: Live ticket board with filter tabs (All, Active, Resolved), 4-stage dispatch stepper progress bars, officer notes, and detailed view modals.
- **Audio Feedback**: Built-in Web Audio API sound cues for tactile clicks, SOS countdown beeps, and dispatch sirens (with mute toggle).
- **Persistent Local Storage**: Submitted tickets and status changes persist in the browser across sessions.

---

## 💻 Local Preview

Run locally using Node:
```bash
node server.js
```
Then open your browser to [http://localhost:3000](http://localhost:3000). Or simply double-click `index.html` to open it in any web browser.
