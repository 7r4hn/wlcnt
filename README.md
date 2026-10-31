# FC 27 W/L Overlay for OBS

A sleek, modern, and ultra-lightweight Win/Loss counter overlay designed for EA Sports FC 27 (and other competitive gaming) streamers. Built with HTML, CSS, and JavaScript, it features an esports-inspired aesthetic and smooth animations without putting any extra load on your system.

## ✨ Features

* **Ultra-Lightweight:** Optimized to run perfectly in OBS without the need for complex background sync scripts.
* **Persistent Memory:** Uses `localStorage` to automatically save your current score. Your W/L record remains intact even if you close or refresh OBS.
* **Dynamic Design:** Features gradient flags with sharply skewed edges, tech-inspired background patterns, and a 3D rotating central logo (spins for 1 second every minute).

## 🚀 How to Install & Control in OBS

1. Add a new **Browser Source** to your OBS scene.
2. Select your local `index.html` file or paste your live GitHub Pages URL.
3. Set **Width** to `276` and **Height** to `146` for the perfect fit.
4. **How to control the score:** In your OBS Sources list, right-click on the Browser Source and select **Interact**.
5. A window will pop up. You can control the counter directly from this window:
   - **Left-Click** on Win/Loss to increase the score.
   - **Right-Click** on Win/Loss to decrease the score.
   - **Click the Logo** to instantly reset the counter to 0-0.

*(Tip: You can drag and drop this Interact window to the edges of your OBS interface to dock it. This gives you a dedicated, lag-free control panel during your stream!)*
