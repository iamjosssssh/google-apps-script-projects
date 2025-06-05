# Google Apps Script Projects

This repository contains over thirty example projects demonstrating Google Apps Script integrations with Sheets, Forms, Docs, Gmail and other services. Each folder in `projects` can be copied into your own Workspace to learn from or adapt.

## Projects Overview

The table below summarises what each project does. Projects with two word names are shown with spaces rather than hyphens.


**Approval App**
- Builds a Vue interface for submitting approval requests.
- Stores requests and user data in a spreadsheet.
- Allows reviewers to update each item's status.

**Blogger View Counter**
- Tracks page views of Blogger posts via an Apps Script web app.
- Stores counts in a spreadsheet.
- Returns JSON data for embedding on the page.

**Booking Cancellation**
- Google Forms allow users to book or cancel appointments.
- Creates and removes calendar events accordingly.
- Sends confirmation emails for each action.

**Calendar Time Tracker**
- Provides a sidebar to log time against calendar events.
- Exposes an API to summarise entries.
- Can email daily reports.

**Calendar Watcher**
- Watches a calendar for event changes using triggers.
- Writes updates to a spreadsheet for tracking.
- Sends email notifications when events are modified.

**ChatGPT Gmail Replies**
- Adds a custom menu in Gmail to create replies with ChatGPT.
- Saves configuration settings in the spreadsheet.
- Generates draft responses ready to review and send.

**ChatGPT in Sheets**
- Connects Google Sheets to the OpenAI API.
- Functions send prompts and write responses back to the sheet.
- Conversation history is stored for reference.

**Dependent Dropdown Form**
- Builds a form with cascading dropdown selections.
- Validates combinations on submission.
- Logs each response to a spreadsheet.

**Drive Folder Sharing**
- Web app to create time limited folder share links.
- Manages allowed folders and access rules in Sheets.
- Emails the generated link to recipients.

**Drive Folder Watcher**
- Monitors a Drive folder for new files.
- Records file metadata to a sheet.
- Trigger runs on a schedule.

**Employee Profile App**
- Simple web interface for managing employee profiles.
- Data is stored in Google Sheets.
- Users can search and update records.

**File Share Automation**
- Processes Drive share requests arriving by email.
- Auto‑approves requests based on a whitelist.
- Logs actions and notifies the requester.

**Form Image Compressor**
- Compresses images uploaded via a Google Form.
- Trigger resizes and saves the files to Drive.
- Reduces storage usage automatically.

**Form Mailman**
- Sends customised emails when a form is submitted.
- Sidebar interface lets you manage templates.
- Installs triggers to process future responses.

**Form to Calendar**
- Creates calendar events directly from form answers.
- Parses dates and times from the responses.
- Emails confirmations to participants.

**Form with Signature**
- Custom form that captures a digital signature image.
- Saves responses along with the signature file.
- Emails a PDF copy of the submission.

**FormSign Doc Signature**
- Users sign a Google Doc via a form workflow.
- Generates a signed copy in Drive.
- Sends notification emails with the document link.

**Gmail Attachment Downloader**
- Searches Gmail for messages with attachments.
- Downloads files to a Drive folder.
- Marks processed emails with a label.

**Gmail Threads to PDF**
- Exports one or more Gmail threads into PDF files.
- Optionally combines multiple messages into one PDF.
- Saves the documents in Drive.

**Gmail Tracker**
- Adds a dialog to send trackable emails.
- Records send and open events in a sheet.
- Generates unique tracking IDs for each message.

**Gmail XML to Sheet**
- Looks for XML attachments in Gmail.
- Parses selected tags and writes data to Sheets.
- Supports filtering out unwanted nodes.

**Html Email Sender**
- Demonstrates sending styled HTML emails.
- Template variables are replaced with data from Sheets.
- Can be extended to send bulk messages.

**Image Annotation**
- Integrates the Vision API to label uploaded images.
- Results are written to a spreadsheet.
- Trigger runs on each form submission.

**Maze Generator**
- Generates random mazes inside Google Sheets.
- Implements Prim’s algorithm.
- Provides demo functions for creating and clearing a maze.

**Merge Docs**
- Merges multiple Docs into a single document.
- Updates status cells in the spreadsheet.
- Returns a link to the merged file.

**Multiple Select Sheet**
- Sidebar UI lets users pick multiple items in a sheet.
- Selected values are written back to the cells.
- Shows how to build an interactive sidebar.

**Options Parser**
- Utility for parsing CSV or JSON style option strings.
- Returns arrays of values for use in scripts.
- Helpful for processing form option lists.

**Personal Time Tracker**
- Tracks time spent on tasks within a spreadsheet.
- Uses a timer and logs entries with start and stop times.
- Can email a summary of hours worked.

**Product Entry Form**
- Dialog for entering new product information.
- Stores submissions in a dedicated sheet.
- Menu item launches the form in the spreadsheet.

**Reservation System**
- Books available slots on a calendar.
- Displays availability and prevents double booking.
- Handles cancellations and updates.

**Rich Text Join Split**
- Example of merging and splitting rich text values.
- Preserves formatting when processing cell text.
- Demonstrates Apps Script rich text APIs.

**Script Copier**
- Copies Apps Script files between projects.
- Handles versioning of destination files.
- Provides a menu to initiate the copy process.

**Send Google Tasks**
- Creates Google Tasks from rows in a sheet.
- Reads due dates, notes and list names from the data.
- Marks tasks as sent once processed.

**SlidePro Automation**
- Generates slides from a template using the SlidePro library.
- Data is pulled from a spreadsheet.
- Produces a final slide deck automatically.

**Weather Forecast**
- Retrieves weather data and writes it to Sheets.
- Adds a custom menu for running the forecast.
- Displays the results in a sidebar or alert.

**YouTube Subtitle Updater**
- Fetches subtitles for a YouTube video through the API.
- Allows editing and re‑uploading the caption file.
- Useful for maintaining multi‑language subtitles.
