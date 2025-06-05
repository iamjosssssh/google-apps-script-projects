# File Share Automation

## Overview
This directory contains the File Share Automation example.

## File Overview
- `README.md` - documentation
- `app.js` - Apps Script
- `appsscript.json` - manifest


## How It Works
- `app.js` scans incoming emails for Drive sharing requests and processes them automatically.
- Approved shares are logged in a spreadsheet and the requester is notified.
- Whitelisted senders bypass manual approval to speed up common requests.
