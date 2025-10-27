# EasyLib

EasyLib is a lightweight, browser-based PDF library that stores your uploaded files locally via IndexedDB. It automatically extracts titles, renders a first-page preview, and lets you manage your collection without any backend services.

## Features
- Import multiple PDF files at once using the built-in uploader.
- Extract titles from PDF metadata (with filename fallback).
- Generate first-page previews powered by [Mozilla PDF.js](https://mozilla.github.io/pdf.js/).
- Persist your library in the browser with IndexedDB for offline access.
- Clean light interface with keyboard-friendly controls.

## Getting Started
1. Open `index.html` in any modern browser (Chrome, Edge, Firefox, or Safari).
2. Click **Import PDFs** and choose one or more files from your computer.
3. Select a card to open the PDF in a new tab, or choose **Remove** to delete it from the library.

> **Note:** Because EasyLib stores data in your browser, clearing site data or using a different device/browser will result in an empty library.

## Development Notes
- All application logic lives in `index.html` for easy hosting on any static server.
- The UI uses a bright, high-contrast palette designed for clarity and readability.
- To reset the local database during development, open the browser dev tools and delete the `easylib` IndexedDB database.

## License
This project is provided for educational purposes. Customize it freely for your needs.
