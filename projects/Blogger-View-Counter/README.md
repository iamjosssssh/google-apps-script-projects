# Blogger View Counter

## Overview
This directory contains the Blogger View Counter example.

## File Overview
- `README.md` - documentation
- `appsscript.json` - manifest
- `post.html` - HTML template
- `postViews.js` - Apps Script


## How It Works
- `postViews.js` exposes a web endpoint that increments page view counts stored in a spreadsheet.
- `post.html` fetches the count for the current Blogger post and displays the number.
- The script records each hit and can return JSON for embedding stats anywhere.
