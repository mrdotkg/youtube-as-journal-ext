# youtube-as-journal-extension

A browser extension that transforms YouTube into a journal-like, distraction-free reading experience with full video titles, watch time, and hidden thumbnails.

![Screenshot of the extension in action](./img/window-screenshot.png)

## ✨ What it does

YouTube As Journal transforms your YouTube browsing into a thoughtful, journal-like experience:
- **Hides distracting thumbnails** across all YouTube pages (home, channel, playlist, search, watch page sidebar)
- **Shows full video titles** without truncation for complete context
- **Displays watch time prominently** by extracting duration from thumbnails and showing it beside titles
- **Preserves essential info** like creator names, view counts, upload dates
- **Multiple display modes** including hidden, hover-to-reveal, blurred, and solid color options

Transform YouTube from a visual-temptation platform into a text-focused, journal-like content discovery tool - perfect for mindful browsing and focusing on content quality over clickbait.

## ✨ Automatic install

Install this extension at:
- [Chrome Web Store](https://chrome.google.com/webstore/detail/hide-youtube-thumbnails/phmcfcbljjdlomoipaffekhgfnpndbef)
- [Firefox Add-ons](https://addons.mozilla.org/en-GB/firefox/addon/hide-youtube-thumbnails/)
- [Edge Add-ons](https://microsoftedge.microsoft.com/addons/detail/hide-youtube-thumbnails/ocgbpppgeepjkmpeahegapfmiefdjcdk)

## 👷 Manual install

1. Clone this repository
2. Go to `chrome://extensions`
3. Enable `Developer mode` in the top right
4. Click `Load unpacked`, and select the cloned folder

## 🚀 Releasing new versions

Common: 

1. Bump version in `manifest.json`
2. Run `./package.sh` to generate `package.zip` (or check the GitHub actions build artifacts)

### Google

1. Go to [the extension in the Chrome Web Store developer dashboard](https://chrome.google.com/webstore/devconsole/6c72c8b9-8c99-4353-8a18-109703f24c82/phmcfcbljjdlomoipaffekhgfnpndbef/edit/package)
2. Click 'Upload new package', and select `package.zip`

### Mozilla Firefox

1. Go to [the extension in the Firefox Add-on Developer Hub](https://addons.mozilla.org/en-GB/developers/addon/hide-youtube-thumbnails/versions/submit/)
2. Click 'Submit a New Version', and select `package.zip`

### Microsoft Edge

1. Go to [the extension in the Microsoft Partner Center for Edge](https://partner.microsoft.com/en-us/dashboard/microsoftedge/d245c788-c342-4166-bd7e-a5f3d9c32ff1/packages/dashboard)
2. Click 'Update', 'Replace', and select `package.zip`
