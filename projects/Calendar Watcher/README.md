# Calendar Watcher

## Overview
This directory contains the Calendar Watcher example.

## File Overview
- `README.md` - documentation
- `app.js` - Apps Script
- `appsscript.json` - manifest


## How It Works
- `app.js` installs calendar event watchers and logs updates to a spreadsheet.
- The script uses triggers to listen for create, update and delete actions.
- When a change occurs an email notification is sent summarising the details.
