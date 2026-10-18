# ReelForge

A responsive, browser based short video editor prototype for creating vertical Instagram Reels and YouTube Shorts from videos you own or are authorized to edit.

## Features

- Import a YouTube link for video identification and thumbnail preview. YouTube links cannot be downloaded or processed by this prototype; upload the source file you have permission to edit.
- Upload a local MP4, MOV, or WebM video; the source stays in the browser.
- Preview, choose vertical or square output, adjust crop, set a short length, add cut markers, and overlay a simple title caption.
- Export the edited result to a downloadable WebM file in the browser.
- Responsive editor layout for desktop and mobile.

## Run locally

Open `index.html` in a recent browser, or serve the repository root with any static web server. Chrome and Edge have the best support for browser video recording.

## Current prototype limits

This version does not extract or download videos from YouTube, generate speech to text captions, identify highlights automatically, or export MP4. Captions use the source filename as placeholder text. The available export is WebM and uses browser `MediaRecorder` and `canvas.captureStream()` support.
