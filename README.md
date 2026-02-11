# CaptionForge
![ScreenRecording2026-02-11at13 06 49-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/27c9fcaa-b1c9-4361-9728-174ac6a28373)

**Free macOS app to convert subtitles or video speech into Final Cut Pro caption-style title clips.**

# CaptionForge

**Turn SRT files or spoken dialogue into frame-accurate Final Cut Pro caption titles.**

CaptionForge is a macOS app that converts subtitle files or spoken dialogue from video into **Final Cut Pro–ready caption title clips**.

Captions are exported as an **FCPXML file** that imports directly into Final Cut Pro, placing each caption as a **title on the timeline** — fully editable, frame-accurate, and easy to customize.

---

## ✨ Features

- Import **SRT subtitle files**
- Generate captions from **video speech** (local macOS Speech Recognition)
- Preview captions before export
- Choose from multiple **caption styles**
- **Frame-accurate timing** (no edit frame boundary warnings)
- Export to **FCPXML** and **SRT**
- Clean, native macOS UI

---

## 🚀 Quick Start

1. Launch **CaptionForge**
2. Choose a caption style from the **Gallery**
3. Load your content:
   - **SRT** → import an existing subtitle file  
   - **Video** → generate captions from spoken dialogue
4. (Optional) Adjust **Max Words**
5. Choose the **Frame Rate** to match your Final Cut Pro timeline
6. Select **Original** or **Processed**
7. Click **Export**
8. Import the exported `.fcpxml` file into Final Cut Pro

---

## 🖼 Caption Style Gallery

When CaptionForge opens, you’ll see the **Gallery**, which displays preview videos of available caption styles.

- Click a preview to select a style and continue
- Click **Skip** to choose a style later
- If caption styles are not installed, click **Install Titles**

You can return to the Gallery at any time using the **Gallery** button.

---

## 📂 Loading Content

### Load an SRT file

1. Select **SRT**
2. Click **Load SRT**
3. Choose a `.srt` file

Captions are loaded and displayed in the **Original** view.

---

### Generate captions from video

1. Select **Video**
2. Click **Load Video**
3. Choose a `.mov`, `.mp4`, or `.m4v` file
4. When prompted, allow **Speech Recognition**
5. Wait for caption generation to complete

> Speech recognition runs locally on your Mac.  
> No audio or video is uploaded.

---

## 🗂 Original vs Processed

CaptionForge shows captions in two views:

### Original

- Shows captions exactly as imported or generated
- Matches the source SRT or speech recognition output
- **Read-only** (cannot be edited)
- Text can be selected and copied

Use **Original** when you want to export captions exactly as they were provided.

---

### Processed

- Shows captions after processing
- Reflects **Max Words** splitting and reflow
- Fully **editable**
- Supports:
  - text editing
  - timing adjustments
  - **Shift + Enter** to split captions
  - merging captions

Use **Processed** to refine caption pacing, readability, and structure.

---

## 📤 Export Behavior (Important)

CaptionForge exports **the view that is currently selected**:

- **Original selected** → exports Original captions
- **Processed selected** → exports Processed captions

> **What you see is what you export.**

This applies to both **FCPXML** and **SRT** exports.

---

## ✏️ Editing Captions

### Original

- Read-only
- No text or timing edits
- Used for reference or direct export

### Processed

- Fully editable
- Edit text directly in the preview
- Adjust caption timing
- Keyboard shortcuts:
  - **Shift + Enter** → split caption
  - Merge captions by removing breaks or using backspace at boundaries

---

## 🎛 Caption Controls

### Max Words

Controls the maximum number of words per caption in the **Processed** view.

- Lower values → shorter captions, more cuts
- Higher values → longer captions, fewer cuts

Changing Max Words affects only the **Processed** view.  
The **Original** view is never modified.

---

### Frame Rate

Choose the frame rate to match your Final Cut Pro timeline:

- 23.976
- 24
- 25
- 29.97
- 30
- 60

CaptionForge exports captions using **exact frame-accurate timing**, including proper NTSC fractional frame rates, so Final Cut Pro imports the XML **without frame-boundary warnings**.

---

## 📤 Exporting to Final Cut Pro

1. Select **Original** or **Processed**
2. Click **Export**
3. Save the `.fcpxml` file
4. In Final Cut Pro, choose **File → Import → XML**
5. Select the exported file

Captions appear as **title clips** in a new project or event.

### Using captions in an existing timeline

If captions import into a new project:

1. Select all caption titles
2. Copy
3. Paste into your working timeline

---

## ☕ Support & Donations

CaptionForge includes a **Support** button (☕) in the app.

- A small indicator highlights it until clicked
- Clicking opens the support panel
- Once clicked, the indicator disappears and stays gone across app launches

Supporting development is optional and always appreciated.

---

## ✅ What CaptionForge Guarantees

- Frame-accurate caption timing
- Clean FCPXML imports
- Fully editable caption titles in Final Cut Pro
- Local-only processing
- macOS-native UI and behavior

---

## 🧠 Tips

- Always match the **Frame Rate** to your Final Cut Pro project
- Use **Original** to preserve existing subtitle structure
- Use **Processed** to improve readability and pacing
- Caption styles can be changed or customized inside Final Cut Pro after import

---

## ☕ Support

If you like the app, feel free to **Buy Me a Coffee** ☕ ❤️

<p align="center">
  <img width="300" height="300" alt="qr-code" src="https://github.com/user-attachments/assets/420fc075-ec21-4e0e-afbb-cc57f75c5f74" />
</p>

