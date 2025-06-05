# Gmail Tracker

## Overview
This directory contains the Gmail Tracker example.

## File Overview
- `README.md` - documentation
- `app.js` - Apps Script
- `appsscript.json` - manifest
- `configs.js` - Apps Script
- `emailForm.html` - HTML template


## How It Works
- `app.js` opens a dialog in Gmail allowing you to send tracked messages.
- `configs.js` defines spreadsheet ranges used to log send and open events.
- The script inserts a unique ID in each email so opens can be recorded.
