# Tappytoon Downloader (ENG, FR, DE)

A custom browser script built to seamlessly intercept and save comic pages from Tappytoon. By hooking directly into the site's network traffic, it grabs the highest quality image files and organizes them into a local directory on your device.

## ✨ Key Features

* **Silent Data Interception:** Monitors background network requests (Fetch/XHR) to capture image URLs the moment they load on the page.
* **Intelligent Page Sorting:** Reads the site's internal sorting data to guarantee every page is saved in the exact correct reading order.
* **Resilient Download Engine:** Built-in smart retry logic. If a page fails to download due to a network hiccup, the script automatically waits and tries again (up to 3 times per image).
* **Floating Progress Monitor:** A dynamic, color-coded button in the bottom right corner keeps you updated on the script's status (Waiting → Ready → Downloading → Done).
* **Auto-Folder Generation:** Groups all downloaded images into a cleanly named folder based on the episode title (e.g., `Downloads/Chapter Title/001.jpg`).
* **Seamless Page Transitions:** Automatically resets and prepares for the next chapter when you navigate to a new episode without needing a page refresh.

## 🚀 Installation Guide

1. **Prerequisite:** Install a userscript manager like **Tampermonkey**.
2. **Get the Script:** Install the latest version directly from [ozler365's Greasyfork](https://greasyfork.org/en/users/1553223-ozler365).
3. **Usage:** Open a chapter on Tappytoon. The floating button will initially say "Wait for Data...".
4. **Download:** Once the data is intercepted, the button turns pink and displays the total page count. Click it to begin saving the images to your device.

## ⚠️ Educational Notice

**This tool is strictly for personal, educational use.** Please support the original artists and platforms. Do not re-upload or distribute the saved media.

## 🔗 Support & Contact

* **GitHub Portfolio:** [ozler-s-works-info](https://ozler365.github.io/ozler-s-works-info/#/repositories)
* **Support My Work:** If this tool saves you time, consider leaving a tip at [Buy Me a Coffee (ozler)](https://buymeacoffee.com/ozler).

For bug reports or feature suggestions, leave a review on Greasyfork or reach out via email at **devjk6918@gmail.com**.
