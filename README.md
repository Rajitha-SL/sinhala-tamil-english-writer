# Sinhala, Tamil, and English Writer

A browser-based typing app with separate Sinhala, Tamil, and English tabs, clickable character keyboards, five font choices per language, and copy/export tools.

## Run it

1. Download or clone this repository.
2. Open `index.html` in a current browser.
3. Select a language tab, choose a font, and type in the editor. The buttons on the left insert characters at the cursor. The vertical bar (`|`) is an ordinary insertable character; it does not switch languages.
4. Use **Copy all**, **Download TXT**, **Download Word**, or **Print / Save PDF** to export your text.

No build step or package installation is needed.

## Font choices

- **Sinhala:** Noto Sans Sinhala, Noto Serif Sinhala, Iskoola Pota, Malithi Web, Arial
- **Tamil:** Noto Sans Tamil, Noto Serif Tamil, Latha, Vijaya, Arial
- **English:** Arial, Times New Roman, Georgia, Verdana, Calibri

The app stores and copies text as Unicode. Font selection changes the display and the font family recorded in the Word export. A selected font must be installed on the computer opening the document; otherwise Word or the browser will use a fallback font. The plain-text export does not retain font styling.

## Input notes

The clickable keyboards insert Unicode characters directly. Physical-keyboard typing in Sinhala or Tamil depends on a Sinhala or Tamil input method enabled in your operating system. This starter does not convert Singlish/Tanglish romanized typing or encode text for legacy FM Bindumathi/Bamini fonts.

## GitHub Pages

To publish a static copy, open the repository on GitHub and go to **Settings → Pages**. Choose **Deploy from a branch**, select `main` and `/(root)`, then save. If GitHub Pages is unavailable for this private repository on your plan, the app can still be used by downloading the repository and opening `index.html` locally.
