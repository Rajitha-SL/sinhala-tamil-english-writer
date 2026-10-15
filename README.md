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

The Sinhala tab has three linked spaces: Singlish/Sinhala typing, editable Sinhala Unicode, and FM Bindumathi legacy output. Typing Singlish in the first space fills the Unicode and FM spaces; typing or pasting Unicode into the second space refreshes the FM output. Use **FM පාඨය පිටපත් කරන්න** to copy the legacy text for a document that uses FM Bindumathi. The Word export and print preview include the converted FM text as well as Unicode text.

The Sinhala transliteration and legacy conversion run in the browser. The FM result is legacy encoded, so it needs the FM Bindumathi font installed in the application where you paste it. Tamil and English tabs remain Unicode text entry; Tamil physical-keyboard typing uses a Tamil input method enabled in your operating system. The Tamil click keyboard inserts Unicode characters.

## GitHub Pages

To publish a static copy, open the repository on GitHub and go to **Settings → Pages**. Choose **Deploy from a branch**, select `main` and `/(root)`, then save. If GitHub Pages is unavailable for this private repository on your plan, the app can still be used by downloading the repository and opening `index.html` locally.
