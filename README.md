# Portable HTML Photo Gallery (`view.html`)

A lightweight, secure, and fully portable photo and video gallery system built with vanilla HTML and JavaScript. 

Designed for self-hosted servers with directory auto-indexing disabled, it allows you to maintain total privacy while providing a rich, responsive browsing experience.

## ✨ Features
* **Zero Dependencies / True Portability:** Drop a single `view.html` file into any media folder, and it automatically scans and renders the contents.
* **Privacy Focused:** Does not rely on public server directory listings.
* **Rich Media Support:** Handles photos (`.jpg`, `.png`, `.webp`, `.gif`, etc.) and videos (`.mp4`, `.webm`, `.mov`) with a built-in fullscreen lightbox and keyboard/swipe navigation.
* **Performance Pagination:** Automatically paginates items (default 48 per page) to prevent browser lag on massive albums.
* **Social Preview Support:** Configured with OpenGraph meta tags so shared links show custom chat previews.
* **Fully Configurable:** Easily customizable branding, return links, and default preview imagery.

## 🚀 Quick Start
1. Drop `view.html` into any directory containing images or videos.
2. Open the file in your browser or share the link (e.g., `https://yourdomain.com/photos/your-folder/view.html`).
3. Customize the `CONFIG` object at the bottom of the script to match your domain and preferred preview image.

## 📄 License
MIT License
