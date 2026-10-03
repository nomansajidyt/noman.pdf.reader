# Noman's PDF Reader

A fast, private PDF reader and note-taking app that runs in one HTML file. Highlight text, attach notes, write notebook pages beside the PDF, and save everything **inside the PDF itself**. Works on laptop, tablet, phone and TV, in light or dark mode.

- No install, no build step, no account, no server
- Your PDFs never leave your device
- Notes live inside the PDF, so they travel with the file

---

## Contents

1. [Quick start](#quick-start)
2. [Opening PDFs](#opening-pdfs)
3. [Reading and navigation](#reading-and-navigation)
4. [Several books at once](#several-books-at-once)
5. [Highlights and notes](#highlights-and-notes)
6. [Note colours and headings](#note-colours-and-headings)
7. [Notebook pages](#notebook-pages)
8. [Saving and AutoSave](#saving-and-autosave)
9. [Closing the tab safely](#closing-the-tab-safely)
10. [Appearance](#appearance)
11. [Phone, tablet, laptop and TV](#phone-tablet-laptop-and-tv)
12. [Keyboard and gesture shortcuts](#keyboard-and-gesture-shortcuts)
13. [Where your data is stored](#where-your-data-is-stored)
14. [Browser support](#browser-support)
15. [Hosting on GitHub Pages](#hosting-on-github-pages)
16. [Troubleshooting](#troubleshooting)
17. [Built with](#built-with)

---

## Quick start

1. Open the app in **Chrome or Edge** (best experience, see [Browser support](#browser-support)).
2. Click **Open a PDF**.
3. Select some text, pick a colour, and type your note.
4. Press **Save PDF** (or just wait, [AutoSave](#saving-and-autosave) does it for you).

Reopen the same PDF any time and your highlights and notes come back.

---

## Opening PDFs

| Way | How |
|---|---|
| Open button | Click the folder icon in the top bar, or **Open a PDF** on the start screen |
| Another book | Click the **+** at the end of the book tabs |
| Several at once | In the file picker, select more than one PDF |
| Drag and drop | Drop one or more PDFs anywhere on the window |

**Remembers your folder.** In Chrome and Edge, the file picker opens in the folder of the last PDF you opened, even after you close the browser. Safari, Firefox and phones decide the starting folder themselves.

**Opening the same file for AutoSave.** Use the Open button (not drag and drop) if you want AutoSave, because only the picker gives the app permission to save back into the file. See [Saving and AutoSave](#saving-and-autosave).

---

## Reading and navigation

- **Previous / next page**: the arrow buttons in the top bar, or the **Left / Right arrow keys**
- **Jump to a page**: type the number in the page box and press Enter. Jumping far through a long book is instant.
- **Zoom**: the **+** and **-** buttons, **Ctrl + mouse wheel**, trackpad pinch, or two-finger pinch on a touch screen
- **Auto fit**: each book opens sized to suit your screen. If you zoom by hand, the app stops resizing it for you.
- **Contents tab**: open the sidebar (menu icon) and use the **Contents** tab to see the PDF outline. Click an entry to go there. Entries with sub-sections expand and collapse.
- **Hover preview** (mouse only): hover a Contents entry and a scrollable preview of that page appears next to the sidebar at your current zoom. Keep scrolling and it continues into the following pages. Move the mouse away to close it.

Pages load as you reach them, nearest first, and fade in. Pages far from the screen are released, so long books stay light.

---

## Several books at once

Each opened PDF gets its own tab under the top bar. Every book keeps its own zoom, scroll position, notes and unsaved-changes status.

- **Switch**: click a tab
- **Close**: click the **x** on the tab (or the **x** in the top bar to close the current book)
- **Unsaved dot**: an amber dot on a tab means that book has changes not yet saved
- **Switch like Alt+Tab**: hold **N** and tap **Tab**. The first tap goes to your previous book; keep tapping Tab to move to older ones; add **Shift** to go backwards. Let go of N to settle on the book you chose.

Closing a book that has unsaved changes asks whether to **Save**, **Discard** or **Cancel**.

---

## Highlights and notes

**Make a highlight with a note**

1. Select text on the page (mouse drag, or long-press on a touch screen).
2. A small toolbar appears. Click a colour.
3. A note window opens. Type your note.

**Work with a note**

- **Reopen**: click a highlight
- **Close**: click anywhere else, or press **Esc**
- **Resize**: drag the grip in the bottom-right corner (mouse, finger or pen). The text re-wraps to fill the window. On phones the note opens as a bottom sheet.
- **Format**: bold, italic, underline, strikethrough, headings, bullet and numbered lists, indent and outdent, text colour. Type `- ` or `1. ` at the start of a line to start a list.
- **Delete**: click the trash icon in the note window. This removes the highlight and its note.
- **Who and when**: each note shows who wrote it (see [student name](#student-name)) and the date and time it was first written. Editing a note later does not change that time.
- **Always fully visible**: the note window moves into view so it is never cut off at the bottom of the screen.

**Notes tab**: open the sidebar and choose **Notes** to see every note in the book, with page, heading, author and date. Click one to jump to it. Use the colour chips at the top to filter the list.

### Student name

Click **Add your name** in the top bar and save it. It is stored on this device and printed on every new note.

---

## Note colours and headings

Each PDF has its own colour set, up to **12 colours**.

- Open the colour editor from the cog in the selection toolbar, or the **Edit** chip in the Notes tab
- **Name a colour** (for example "Definition", "Question", "Exam tip"). The name becomes the heading shown on notes of that colour and in the Notes list.
- **Add a colour**, **change a colour**, or **remove** one (at least one colour must stay)
- Changing a colour recolours the notes that use it
- Reset returns to the default set

Colours and names are saved inside the PDF, so they stay with that book.

---

## Notebook pages

A free-writing page next to every PDF page, for your own summaries.

- Turn it on or off with the **Notebook** button in the top bar
- It is on by default on laptop and TV screens, and off on phones. Your choice is remembered.
- Click a notebook page and type. A formatting bar appears at the bottom while you edit: bold, italic, underline, strikethrough, headings, lists, indent, text colour, clear formatting.
- **Paste from Word or Google Docs**: formatting such as bold, lists, headings, links and colours is kept; everything else is cleaned away
- Notebook text is saved into the PDF, and also written as a plain-text sticky note so other PDF programs can show it

---

## Saving and AutoSave

**What is saved:** your highlights, notes, colour set and notebook pages are written **into the PDF file**. They are standard highlight and sticky-note annotations, plus an embedded data block this app reads back, so the file still opens normally in other PDF programs.

### Save PDF

Click **Save PDF** in the top bar. The button shows a dot when there are unsaved changes and flashes green when saved.

- **Chrome / Edge, opened with the Open button**: saves straight back into the same file
- **Other browsers, or files opened by drag and drop**: downloads an updated copy. Replace your original with it.

### AutoSave

Like Word's AutoSave: changes are saved into the file **2 minutes after you make them**, and not while you are typing.

The AutoSave switch in the top bar shows its state:

| State | Meaning |
|---|---|
| **On** (green) | Changes save into the PDF automatically |
| **Allow** (amber) | The browser needs your permission to write to the file. Click the switch and allow. |
| **Off** | You turned it off. Click to turn it back on. |
| Off for this book | The book was opened without a link to its file. Click the switch, then **Connect file** and choose the same PDF, or reopen it with the Open button. |

AutoSave needs Chrome or Edge on a computer. The switch is hidden on phones.

---

## Closing the tab safely

If any book has unsaved changes when you close the browser tab:

1. The browser shows its own "Leave site?" message (browsers do not allow anything else).
2. Choose **Stay**. A window opens listing the unsaved books, each with a **Save / Discard** choice.
3. Use **Save all**, **Discard all**, or **Apply my choices**, then close the tab again.

**Discard** puts a book's notes back to how they were at the last save.

---

## Appearance

- **Light / dark**: the moon button in the top bar. The change fades in smoothly.
- **Dark pages**: in dark mode the PDF page itself turns dark with light text. The half-circle button next to **Aa** turns this off if you prefer white pages inside a dark app (useful for picture-heavy PDFs).
- **Text darkness (Aa)**: cycles Normal, Bold, Extra bold. Makes thin or faint text easier to read.
- **Motion**: gentle animations throughout. If your system is set to "reduce motion", they are switched off.

---

## Phone, tablet, laptop and TV

The app detects your device and adjusts, including when you rotate or resize.

| Device | What changes |
|---|---|
| **Phone** | Sidebar slides over the page. Compact top bar. Notes open as a bottom sheet. Pinch to zoom. Notebook pages and AutoSave switch are hidden. |
| **Tablet** | Sidebar slides over on narrower screens. Larger touch targets. Page fits the screen width. |
| **Laptop** | Sidebar beside the page. Large resizable note window. Hover preview. Trackpad pinch or Ctrl + wheel zoom. |
| **TV** | Larger interface and text, visible focus outline, remote arrow keys turn pages and Enter presses the focused button. |

On touch screens: long-press text to select, tap a highlight to open its note, pinch to zoom.

---

## Keyboard and gesture shortcuts

| Action | Shortcut |
|---|---|
| Next / previous page | Right / Left arrow |
| Switch between open books | Hold **N**, tap **Tab** (add **Shift** to go back) |
| Close note or selection toolbar | **Esc** |
| Zoom | **Ctrl + wheel**, trackpad pinch, touch pinch |
| Bold / italic / underline in a note | **Ctrl+B** / **Ctrl+I** / **Ctrl+U** |
| Indent / outdent a list item | **Tab** / **Shift+Tab** |
| Start a list | Type `- ` or `1. ` at the start of a line |

Holding N while typing in a note types "n" characters, so use the book switcher outside note boxes.

---

## Where your data is stored

Everything stays on your device. Nothing is uploaded anywhere.

| What | Where |
|---|---|
| Highlights, notes, colours, notebook pages | **Inside your PDF file** |
| Light/dark, student name, text darkness, dark-pages choice, notebook on/off, AutoSave on/off | Browser `localStorage` for this site |
| Link to the last opened file (so the picker opens in the same folder) | Browser `IndexedDB` (`nomans-reader`) |

Clearing your browser's site data for this app resets those preferences and the remembered folder. Your PDFs and the notes inside them are not affected.

---

## Browser support

| Browser | Reading and notes | Save back into the file | AutoSave | Remembered folder |
|---|---|---|---|---|
| Chrome / Edge (computer) | Yes | Yes | Yes | Yes |
| Chrome (Android) | Yes | Downloads a copy | No | No |
| Safari (Mac, iPhone, iPad) | Yes | Downloads a copy | No | No |
| Firefox | Yes | Downloads a copy | No | No |

On iPhone and iPad, after **Save PDF** downloads the copy, move it back into your Files, iCloud Drive or OneDrive folder.

The app loads its two PDF libraries from the internet (see [Built with](#built-with)), so it needs a connection the first time. Browsers usually cache them afterwards.

---

## Hosting on GitHub Pages

1. Rename the app file to `index.html` and put it in a GitHub repository (with this `README.md`).
2. In the repository, go to **Settings, then Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick your branch (for example `main`) and the `/ (root)` folder, then save.
4. After a minute your app is live at `https://<your-username>.github.io/<repository-name>/`.
5. On a phone, open that address and use **Share, then Add to Home Screen** to get an app icon.

Hosting over `https://` also lets AutoSave and the remembered folder work properly in Chrome and Edge.

---

## Troubleshooting

**The page looks blank or nothing opens.**
Check your internet connection. The PDF libraries load from a CDN on first use.

**Save PDF downloads a file instead of saving in place.**
Your browser or the way you opened the file does not allow saving in place. Use Chrome or Edge and open the PDF with the Open button (not drag and drop). For other cases, replace the original with the downloaded copy.

**AutoSave shows "Allow".**
Click the switch and approve the browser's permission prompt.

**AutoSave says it is off for this book.**
Click the switch, choose **Connect file**, and pick the same PDF.

**My notes do not show in another PDF program.**
Highlights and sticky notes are standard annotations and should appear in most readers. Rich formatting inside a note may show as plain text there.

**Text looks too thin.**
Press the **Aa** button to make text bolder.

**Dark mode makes images look odd.**
Press the half-circle button next to **Aa** to keep pages white in dark mode.

**The tab icon did not update.**
Browsers cache tab icons. Refresh or reopen the page.

---

## Built with

- [PDF.js](https://mozilla.github.io/pdf.js/) 3.11.174 for drawing pages and text (loaded from cdnjs)
- [pdf-lib](https://pdf-lib.js.org/) 1.17.1 for writing notes into PDFs (loaded from cdnjs)
- Plain HTML, CSS and JavaScript. No framework, no build tools.
