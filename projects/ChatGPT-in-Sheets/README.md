# ChatGPT in Sheets

## Overview
This directory contains the ChatGPT in Sheets example.

## File Overview
- `utils.js` - Apps Script
- `app.js` - Apps Script
- `README.md` - documentation
- `appsscript.json` - manifest


## How It Works
- `app.js` adds custom functions and menus in Sheets to send prompts to ChatGPT.
- `utils.js` handles the HTTP requests to the OpenAI API and writes results back to the sheet.
- The script remembers previous conversations so follow-up prompts maintain context.
