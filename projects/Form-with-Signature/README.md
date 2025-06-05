# Form with Signature

## Overview
This directory contains the Form with Signature example.

## File Overview
- `README.md` - documentation
- `appsscript.json` - manifest
- `backend.js` - Apps Script
- `index.html` - HTML template
- `vuejs.html` - HTML template


## How It Works
- `backend.js` serves a custom form that captures a signature image along with other fields.
- Submitted data is stored in a sheet and the signature is saved as an image in Drive.
- `index.html` and `vuejs.html` provide the front end using Vue to draw the signature pad.
