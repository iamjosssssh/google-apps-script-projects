# Approval App

## Overview
This directory contains the Approval App example.

## File Overview
- `README.md` - documentation
- `appsscript.json` - manifest
- `backend.js` - Apps Script
- `css.html` - HTML template
- `index.html` - HTML template
- `utils.html` - HTML template
- `vue` - folder


## How It Works
- `backend.js` stores requests and user info in the spreadsheet and serves data to the Vue front end.
- `index.html` together with templates in the `vue` folder renders the request form and lists approvals.
- `css.html` and `utils.html` provide styling and helper functions shared by the pages.
- Users submit approvals which reviewers can then approve or reject from the interface.
