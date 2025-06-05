# Form Image Compressor

## Overview
This directory contains the Form Image Compressor example.

## File Overview
- `README.md` - documentation
- `appsscript.json` - manifest
- `code.js` - Apps Script
- `utils.js` - Apps Script


## How It Works
- `code.js` listens for new form submissions and compresses any uploaded images.
- `utils.js` handles the Drive file manipulation and resizing operations.
- Compressed files are stored in a Drive folder while the original responses remain intact.
