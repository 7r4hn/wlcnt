# FC 27 W/L Overlay for OBS

<p align="center">
  <img alt="FC 27 W/L Overlay" src="https://img.shields.io/badge/OBS-Compatible-5B5BFF?style=for-the-badge&logo=obsstudio" />
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5" />
  <img alt="Lightweight" src="https://img.shields.io/badge/Weight-Ultra%20Light-00C853?style=for-the-badge" />
  <img alt="Persistent" src="https://img.shields.io/badge/Storage-localStorage-FF9800?style=for-the-badge" />
</p>

A sleek, modern, and ultra-lightweight Win/Loss counter overlay designed for EA Sports FC 27 streamers and competitive gamers. Built with plain HTML, CSS, and JavaScript, it gives your stream an elegant scoreboard without any heavy dependencies.

## Live browser source

The project is published as a GitHub Pages page and can be used directly in OBS as a Browser Source:

- URL: https://7r4hn.github.io/wlcnt/

This is the recommended way to use the overlay in OBS because it keeps the project clean and ready to load without needing a local file.

## Why this overlay?

- Ultra-lightweight and optimized for OBS use
- Saves your score automatically using `localStorage`
- Easy to control directly from the browser source interaction window
- Clean, modern design with a rotating logo animation and sharp, tech-inspired styling
- Works perfectly as a local file or a hosted web page

## Features

- Persistent memory so your W/L record survives refreshes and restarts
- Minimal system impact with no heavy dependencies
- Responsive, compact layout tuned for stream overlays
- Simple score interaction controls:
  - Left click to increase
  - Right click to decrease
  - Logo click to reset to `0-0`
- Designed for FC 27 and other competitive gaming setups

## Quick start

### Use in OBS

1. Open OBS.
2. Add a new Browser Source.
3. Set the URL to:
   - https://7r4hn.github.io/wlcnt/
4. Set the dimensions to:
   - Width: `276`
   - Height: `146`
5. Click OK and start using the overlay.

### Local file option

If you want to test locally:

1. Open the project folder in your browser.
2. Use `index.html` directly.
3. Or open it from a local server if you prefer.

## Controls

In OBS, right-click the Browser Source and select `Interact`.

From the pop-up window, you can control the overlay directly:

- Left-click the Win/Loss display to increase the score
- Right-click the Win/Loss display to decrease the score
- Click the central logo to reset the counter to `0-0`

This makes it easy to manage your score without needing extra software or hotkeys.

## Tips

- Drag the interaction window to the edge of your OBS layout to keep it docked while streaming.
- Keep the Browser Source in a compact, fixed-size canvas for the cleanest look.
- Because it uses `localStorage`, your current record stays saved between sessions.
- If the page does not load in OBS, refresh the browser source or confirm the GitHub Pages URL is exactly correct.

## Project structure

```text
.
├── index.html
├── champs.svg
├── README.md
├── test-assets/
│   ├── win-preview.svg
│   └── loss-preview.svg
└── .github/
```

## Demo

This overlay is designed to be used as a compact OBS widget and is best showcased in a live stream environment. For the best visual result, use it in a scene with a clean, dark background.

## License

This project is open for personal and stream-use customization.

## Support

If you want to extend it with:

- team names
- round or map tracking
- custom colors
- animated transitions

this overlay is easy to adapt for your own style.
