# ReelForge

A responsive, browser based short video editor prototype for creating vertical Instagram Reels and YouTube Shorts from videos you own or are authorized to edit.

## Features

- Import a YouTube link for video identification and thumbnail preview. YouTube links cannot be downloaded or processed by this prototype; upload the source file you have permission to edit.
- Upload a local MP4, MOV, or WebM video; the source stays in the browser.
- Choose vertical or square output, use fit-with-blurred-background or fill-and-crop, set a start point and clip length, and adjust playback speed.
- Select a color look, caption text, caption style and placement, and original-audio toggle.
- Add multiple shots from the source video and export them stitched in order; undo the last selected shot.
- Export 1080p or 720p WebM in the browser.
- Responsive editor layout for desktop and mobile.

## Run locally

Open `index.html` in a recent browser, or serve the repository root with any static web server. Chrome and Edge have the best support for browser video recording.

## Current prototype limits

This version does not extract or download videos from YouTube, generate speech-to-text captions, automatically identify highlights, mix in a separate soundtrack, or export MP4. The available export is WebM and uses browser `MediaRecorder` and `canvas.captureStream()` support.
