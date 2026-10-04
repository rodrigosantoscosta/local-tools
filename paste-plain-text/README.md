# Paste Plain Text

Paste formatted text (from Word, web pages, emails, etc.) and get clean plain text, ready to copy.

## Features

- Input area ("Paste here") with a character counter.
- Output area ("Plain text") with a character counter.
- Cleanup options:
  - Trim leading and trailing spaces
  - Collapse repeated spaces
  - Remove extra line breaks
  - Remove all line breaks
- Buttons: **Copy plain text**, **Paste from clipboard**, **Clear**.
- Theme toggle (light/dark).

## How to use

1. Open `index.html` in your browser.
2. Paste your content into the input box (Ctrl+V) or click "Paste from clipboard".
3. Check the cleanup options you want.
4. Click "Copy plain text" and paste it wherever you need.

## Privacy

All processing happens in your browser. Nothing is sent to any server.

## Notes

- The "Paste from clipboard" button relies on the Clipboard API, which requires a secure context (HTTPS or `localhost`) and browser permission. When opened via `file://`, support may vary. If it fails, use Ctrl+V.
- The interface is in English.

## Tech

Plain HTML, CSS and JavaScript, no dependencies.
