# Joseph J. Hay - Author Portfolio

[![Live Site](https://img.shields.io/badge/Live_Site-View_Now-blue?style=for-the-badge)](https://joseph-j-hay.pages.dev/)
[![Cloudflare Pages](https://img.shields.io/badge/Hosted_on-Cloudflare_Pages-F38020?style=for-the-badge&logo=cloudflare)](https://pages.cloudflare.com/)

A professional, responsive portfolio and landing page for **Joseph J. Hay**, military veteran and author. This site serves as a central hub to showcase his book collection, share his unique perspective, and direct readers to his Amazon Author page.

## 📖 Featured Books

This landing page highlights the following titles:
1. **The True Middle:** Connections & Perspective
2. **Emotional Equity:** Investment & Self-Reflection
3. **The Space Between Us:** Individuality & Coexistence

## ✨ Features

- **Clean, Modern UI:** A distraction-free design focused on typography and imagery.
- **Responsive Design:** Fully optimized for mobile, tablet, and desktop viewing.
- **Amazon Integration:** Direct outbound links to Amazon product pages and the official Author page.
- **Fast Performance:** Lightweight static assets served globally via Cloudflare's edge network.

## 🛠️ Tech Stack

- **Frontend:** Semantic HTML5, CSS3 
- **Hosting & CI/CD:** [Cloudflare Pages](https://pages.cloudflare.com/)

## 📂 Project Structure

```text
joseph-j-hay-cloudflare-site/
├── assets/             # Images, book covers, and fonts
├── index.html          # Main landing page template
├── styles.css          # Global styling (if separate from HTML)
└── README.md           # Project documentation
```

## 🚀 Local Development

To run this project locally, you don't need any complex build tools. You can use any local web server.

### Option 1: VS Code (Recommended)
1. Open the project folder in Visual Studio Code.
2. Install the **Live Server** extension.
3. Right-click on `index.html` and select **"Open with Live Server"**.
4. The site will open in your default browser at `http://127.0.0.1:5500`.

### Option 2: Python HTTP Server
If you have Python installed, open your terminal, navigate to this directory, and run:
```bash
# Python 3
python -m http.server 8000
```
Then open `http://localhost:8000` in your browser.

## ☁️ Deployment

This project is configured for continuous deployment using **Cloudflare Pages**. 

1. Any push to the `main` branch of this GitHub repository will automatically trigger a new build.
2. Cloudflare fetches the latest code and deploys it to the live edge network in seconds.
3. The live site can be accessed at: [https://joseph-j-hay.pages.dev/](https://joseph-j-hay.pages.dev/)

## 🤝 Contact & Links

- **Live Website:** [joseph-j-hay.pages.dev](https://joseph-j-hay.pages.dev/)
