# Praveen Kumar · CCNA | Network & IT Support — Portfolio

Personal portfolio website of **Praveen Kumar**, a CCNA certified Networking & IT Support professional with hands-on experience in routing, switching, VLANs, DHCP, DNS, NAT, IPv4/IPv6, desktop support and large-scale academic operations.

🌐 **Live site:** https://praveenkumarmsk.github.io/My_Profile_Portfolio/

---

## ✨ Features

- NOC / terminal-style design with an animated network-topology background
- Typing terminal in the hero section (`Praveen# show version`)
- Dark / Light theme toggle (remembers your choice)
- Sections: Home, About, Skills, Certifications, Experience, Projects (Networking Labs), GitHub, Contact, Resume
- **Auto-updating GitHub section** — all public repos are loaded from the GitHub API, so new repos appear automatically (falls back to a built-in list if the API is unavailable)
- Experience timeline and "Moments @ Physics Wallah" photo gallery with lightbox
- Fully responsive (mobile, tablet, desktop)
- Single-file site: pure HTML, CSS and JavaScript — no build step, no dependencies

---

## 📁 Project Structure

```
My_Profile_Portfolio/
├── index.html                 # Complete website (HTML + CSS + JS)
├── README.md
├── .github/workflows/         # GitHub Pages deployment workflow
└── assets/
    ├── images/
    │   ├── profile.jpg
    │   └── pw-moment-1.jpg … pw-moment-9.jpeg
    ├── certificates/
    │   ├── ccna-certificate.jpg
    │   └── adca-certificate.png
    └── docs/
        └── Praveen Kumar CCNA CV_New.pdf
```

---

## 🚀 Run Locally

No installation needed.

1. Clone the repository
   ```bash
   git clone https://github.com/PraveenKumarmsk/My_Profile_Portfolio.git
   cd My_Profile_Portfolio
   ```
2. Open `index.html` in your browser, or serve it locally:
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`.

---

## 🌍 Deploy on GitHub Pages

1. Push the files to the `main` branch.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select the `main` branch (root) or **GitHub Actions** (if using the workflow in `.github/workflows`).
4. Your site will be live at `https://<username>.github.io/My_Profile_Portfolio/`.

---

## 🛠️ Customize

| What to change | Where |
|---|---|
| Profile photo | Replace `assets/images/profile.jpg` |
| Certificates | Add/replace files in `assets/certificates/` (same file names) |
| Resume | Replace the PDF in `assets/docs/` (keep the same file name) |
| Gallery photos | `assets/images/pw-moment-1…9` |
| Contact details & links | Contact section in `index.html` |
| GitHub username for auto repos | `USER` variable in the GitHub script inside `index.html` |

---

## 🧰 Tech Stack

HTML5 · CSS3 · Vanilla JavaScript · GitHub Pages · GitHub REST API

---

## 📬 Contact

- 📧 Email: krpravin406@gmail.com
- 💬 WhatsApp: [wa.me/phone_no](https://wa.me/916299078085)
- 💼 LinkedIn: [praveen-kumar-msk](https://www.linkedin.com/in/praveen-kumar-msk/)
- 🐙 GitHub: [PraveenKumarmsk](https://github.com/PraveenKumarmsk)

---
## 📄 License

Copyright © 2026 Praveen Kumar. All Rights Reserved.

This project is proprietary. Unauthorized copying, modification, distribution, or commercial use of the source code is prohibited without prior written permission from the copyright owner.

For more information, see the [LICENSE](LICENSE) file.
