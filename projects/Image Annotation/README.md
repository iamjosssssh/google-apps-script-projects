# Image Annotation

## Overview
This directory contains the Image Annotation example.

## File Overview
- `README.md` - documentation
- `appsscript.json` - manifest
- `forms.js` - Apps Script
- `main.js` - Apps Script
- `sheets.js` - Apps Script
- `vision.js` - Apps Script


## How It Works
- `forms.js` handles file uploads via a Google Form and passes them to the Vision API.
- `vision.js` detects labels for each image and `sheets.js` records the results.
- `main.js` coordinates the process and schedules triggers for new submissions.
