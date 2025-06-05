# Gmail XML to Sheet

## Overview
This directory contains the Gmail XML to Sheet example.

## File Overview
- `README.md` - documentation
- `app.js` - Apps Script
- `appsscript.json` - manifest
- `sidebar.html` - HTML template


## How It Works
- `app.js` searches Gmail for messages with XML attachments and parses specific tags.
- Parsed data rows are written to a Google Sheet via the sidebar interface.
- Unwanted nodes can be ignored through simple filtering functions.
