# deleteGmailSpamAndTrash
This script is awesome solution against spam and trash in Gmail.

# Gmail Auto-Cleaner

This Google Apps Script automatically empties Spam and Trash in Gmail using the Gmail API.

## Features
- Permanently deletes all threads in Spam and Trash.
- Uses fallback to remove individual messages if thread deletion fails.
- Can be scheduled via time-driven triggers.

## Requirements
- Gmail API enabled in Google Apps Script Advanced Services.
- Authorization to manage Gmail threads/messages.

## Usage
1. Copy the script to [Google Apps Script](https://script.google.com/).
2. Enable Gmail API in Advanced Services.
3. Run `forceEmptyTrashAndSpam` once to authorize.
4. Optional: Add a time-driven trigger to run daily.

## License
MIT License
