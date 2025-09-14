# LeadTracker - Chrome Extension

LeadTracker is a lightweight and efficient Chrome extension designed to help users save leads directly from their browser. With a simple and intuitive interface, users can quickly store URLs either by manual input or by saving the current browser tab, making it an ideal tool for sales professionals, recruiters, researchers, and anyone who needs to keep track of important web resources (e.g. "Read Later").

## Features

- **Save Leads Instantly:** Add URLs manually or save the current tab with a single click.
- **Persistent Storage:** All leads are stored in your browser's local storage for quick access and reliability.
- **Easy Management:** View your saved leads in a clean list and delete all with a double-click.
- **Minimalist UI:** Simple, distraction-free design for maximum productivity.

## Installation

1. Clone or download this repository.
2. Open Chrome and navigate to `chrome://extensions/`.
3. Enable "Developer mode" (top right corner).
4. Click "Load unpacked" and select the project directory.
5. The LeadTracker icon will appear in your Chrome toolbar.

## Usage

- **Save Input:** Enter a URL in the input field and click "SAVE INPUT" to add it to your leads list.
- **Save Tab:** Click "SAVE TAB" to instantly save the URL of your current browser tab.
- **Delete All:** Double-click the "DELETE ALL" button to clear all saved leads.
- **Access Leads:** Click any saved link in the list to open it in a new tab.

## Technical Details

- **Frontend:** HTML, CSS, JavaScript (Vanilla)
- **Chrome APIs:** Uses the `chrome.tabs` API for tab management.
- **Storage:** Utilizes `localStorage` for persistent data.
- **Manifest V3:** Built with the latest Chrome extension standards.

## File Structure

- `index.html` – Popup UI
- `index.js` – Extension logic
- `index.css` – Styling
- `manifest.json` – Chrome extension configuration

## Screenshots

![Screenshot of the LeadTracker Chrome Extension](image.png)

## About This Project
This solo project was part of the Full Stack Developer Path on Scrimba. It was developed in roughly 1 hour as a coding exercise.

Feel free to use, modify, or extend this project. Feedback and contributions are welcome!

---

**Author:** Christoph Thiers  
**Contact:** [(https://www.linkedin.com/in/christophthiers/)]
