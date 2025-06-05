# YouTube Subtitle Updater

## Overview
This directory contains the YouTube Subtitle Updater example.

## File Overview
- `revision.js` - Apps Script
- `utils.js` - Apps Script
- `api.js` - Apps Script
- `main.js` - Apps Script
- `README.md` - documentation
- `appsscript.json` - manifest


## How It Works
- `api.js` connects to the YouTube Data API to download, update and reupload subtitle tracks.
- `main.js` provides menu commands for selecting a video and applying subtitle edits.
- `revision.js` keeps track of caption file versions in Drive while `utils.js` handles configuration.
