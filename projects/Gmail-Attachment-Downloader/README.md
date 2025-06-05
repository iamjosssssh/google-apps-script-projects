# Gmail Attachment Downloader

## Overview
This directory contains the Gmail Attachment Downloader example.

## File Overview
- `README.md` - documentation
- `app.js` - Apps Script
- `appsscript.json` - manifest
- `logEmail.html` - HTML template


## How It Works
- `app.js` searches Gmail for messages with attachments and downloads them to Drive.
- `logEmail.html` provides a simple log window showing processed messages.
- Labels are added to mark emails that have already been handled.
