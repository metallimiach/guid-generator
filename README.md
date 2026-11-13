# Fast & Free GUID / UUID Generator

A lightning-fast, secure, and lightweight web utility to generate cryptographically secure UUIDs instantly in your browser. Built with performance, privacy, and developer experience in mind.

---

## ✨ Features

- **Multiple Formats & Versions:**
  - **UUID v4 (Random):** Standard cryptographically secure random UUIDs.
  - **UUID v7 (Time-ordered):** Modern timestamp-based UUIDs (ideal for database primary keys).
  - **Nil / Empty GUID:** `00000000-0000-0000-0000-000000000000` generation.
- **Customizable Options:**
  - Bulk generation (1 to 50 IDs at once).
  - Uppercase / Lowercase formatting.
  - Optional hyphens (`-`).
  - Optional Microsoft-style curly braces (`{...}`).
- **Robust Copy Utility:** One-click batch copy with instant visual and accessible feedback (with fallback handling for older environments).
- **100% Private & Client-Side:** No data or generated IDs are ever sent to any server. Powered entirely by native browser cryptographic APIs (`crypto.randomUUID()` / `crypto.getRandomValues()`).
- **Zero Dependencies:** Pure HTML5, CSS (Tailwind via CDN), and Vanilla JavaScript — no heavy frontend frameworks, loads instantly.

---

## 🛠️ Tech Stack

- **Markup:** HTML5
- **Styling:** Tailwind CSS
- **Logic:** Vanilla JavaScript (ES6+)

---

## 🚀 Running Locally

Because this is a static client-side application, you don't need Node.js, npm, or complex build tools to run it.

1. Clone the repository:
   ```bash
   git clone https://github.com/metallimiach/guid-generator.git
   ```
2. Open `index.html` in your browser.
