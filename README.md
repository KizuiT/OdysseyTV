# Odyssey TV

A personal screening room for saving and watching video links in one place. Add a video URL or an `<iframe>` embed, give it a title, and play it from your library.

## Features

- Save embedded video links in a library stored in your browser.
- Search your collection and sort it by date added or title.
- Open saved videos in a distraction-free theater view.
- Add or remove screenings at any time.
- Use the responsive interface on desktop and mobile.

## Getting started

No build tools or installation are required.

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Select **Add Screening**, paste a video URL or iframe embed code, and save it.
4. Select a screening in your library to open theater mode.

Your library is stored in local browser storage on the device and browser you use. It is not synced between devices.

## Supported links

Odyssey TV accepts HTTP and HTTPS URLs and extracts the URL from standard iframe embed code. Whether a link plays inside the theater depends on the video provider: some sites prohibit embedding, require an official embed URL, or restrict playback by account, network, or region. Use **Open source** in theater mode to try the link directly.

## Publish with GitHub Pages

1. Open the repository's **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Choose the `main` branch and the `/(root)` folder, then save.
4. Once the deployment completes, open the URL shown in the Pages settings.

GitHub Pages serves `index.html` from the repository root as the home page.

## Privacy

Saved titles and links remain in your browser's local storage. When you play a screening, its provider receives a request from your browser and may apply its own privacy policy and tracking.

## License

See [LICENSE](LICENSE).
