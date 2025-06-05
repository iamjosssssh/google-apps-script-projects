# Reservation System

## Overview
This directory contains the Reservation System example.

## File Overview
- `README.md` - documentation
- `app.js` - Apps Script
- `appsscript.json` - manifest


## How It Works
- `app.js` maintains a calendar of bookable slots and handles reservation requests.
- When a user books or cancels, the spreadsheet and calendar are both updated.
- The script prevents double bookings by checking for conflicts before adding events.
