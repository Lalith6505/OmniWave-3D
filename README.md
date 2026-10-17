# OmniWave 3D — Official Webpage & Privacy Policy for GitHub Deploy

This folder contains the complete, standalone static webpage and Google Play-compliant Privacy Policy for **OmniWave 3D: Quantum Sensory Lab & Acoustic Chrono-Scanner** (`com.omniwave.sensorylab`), designed and engineered by **Lalith Madanayake**.

---

## 📁 Included Files

| File | Purpose |
|---|---|
| `index.html` | Interactive, responsive landing page featuring a live HTML5 Canvas CRT Oscilloscope & Radar simulation, 4-domain interactive switcher, Web Audio API chimes, technical specifications, and direct APK download button. |
| `privacy.html` | Standalone, comprehensive legal Privacy Policy explicitly meeting Google Play Console disclosure standards for Microphone (`RECORD_AUDIO`), 400Hz accelerometer kinetics, optical strobe detection, and 100% offline architecture. |
| `icon_512.png` | Official high-resolution 512×512 app icon. |
| `feature_banner_1024x500.png` | Official 1024×500 promotional banner for OpenGraph social preview cards. |
| `OmniWave-1.0.0-release.apk` | Signed release APK ready for direct downloads from the webpage. |
| `.nojekyll` | Bypasses Jekyll static generator on GitHub Pages to serve all files cleanly. |

---

## 🚀 Quick 2-Minute Deployment to GitHub Pages

### Method 1: Using GitHub Web Interface (No Command Line Needed)
1. Go to [github.com/new](https://github.com/new) and create a new public repository named `omniwave-3d` (or `omniwave-sensorylab`).
2. Click **"uploading an existing file"**.
3. Drag and drop all files from this `github-pages` folder into the repository.
4. Click **Commit changes**.
5. In your repository, go to **Settings** → **Pages** (in the left sidebar).
6. Under **Branch**, select `main` and `/ (root)`, then click **Save**.
7. Within 60 seconds, your site is live!

---

### Method 2: Using Git Command Line
Open PowerShell or your terminal in this `github-pages` folder and run:

```bash
git init
git add .
git commit -m "Deploy OmniWave 3D website and privacy policy"
git branch -M main
git remote add origin https://github.com/lmadanayake/omniwave-3d.git
git push -u origin main
```

Then enable GitHub Pages under **Repository Settings → Pages → Deploy from branch (main / root)**.

---

## 🔗 Your Live URLs for Google Play Console

Once deployed on GitHub Pages:

- **Main Webpage:**  
  `https://lmadanayake.github.io/omniwave-3d/`

- **Privacy Policy URL (Submit this in Google Play Console):**  
  `https://lmadanayake.github.io/omniwave-3d/privacy.html`

> In Google Play Console, navigate to:  
> **Policy and programs → App content → Privacy policy → Add privacy policy URL**  
> Paste the `privacy.html` URL above.

---

### 👨‍💻 Engineering Attribution
- **Developer:** Lalith Madanayake
- **Organization:** Mobile Applications Development
- **Email:** lmadanayake@gmail.com
- **Location:** Colombo, Western Province, Sri Lanka
