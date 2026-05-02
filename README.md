# Prashanth PDF Merger 📄

A clean, browser-based PDF merger built by Prashanth Goud.

No sign-up ✅
No backend upload 🔒
No watermark 🧼

Just merge your PDF files quickly and safely ⚡

## Live App 🌐
https://pdfmerger-snowy.vercel.app/ 

## What This Project Does 🧠
- Merges multiple PDF files into one downloadable PDF
- Runs fully in the browser
- Lets users reorder files before merge
- Shows PDF previews and page counts
- Supports dark/light theme
- Gives keyboard shortcuts for speed

## Features ✨
- Maximum 15 PDF files in one merge
- Maximum 150 MB total upload size
- Drag and drop file upload
- Drag to reorder files
- File thumbnail preview
- Page count extraction
- Custom output file name
- Real-time merge progress
- Share option after merge
- Space key to merge
- Escape key to clear all files

## Tech Stack 🛠️
- React (Create React App)
- Tailwind CSS
- PDF.js (read/render pages)
- jsPDF (build merged output)
- Lucide React (icons)

## How Merge Works 🔄
1. User uploads PDF files.
2. App validates file type, file count, and total size.
3. PDF.js reads each PDF and renders pages into canvas.
4. jsPDF inserts rendered pages into a new output PDF.
5. Final merged file is downloaded to the user's device.

## Privacy 🔐
All processing happens on the client side (inside browser).

Your files are not sent to any external server by this app.

## Local Setup 🚀
```bash
git clone  : https://github.com/Prashanthgoud15/PdfMerger.git
cd pdf-merger
npm install
npm start
```

## Project Structure 📁
```text
src/
	App.js
	index.js
	index.css
	components/
		PDFMerger.jsx
```

## Coded by 👨‍💻
Prashanth Goud

LinkedIn 🔗:
https://www.linkedin.com/in/prashanth-goud-372485294/
