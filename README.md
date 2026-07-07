# AI Financial Document Organizer

## Business Problem
Finance teams often receive daily financial documents through email and manually download, rename, organize, and store them in the correct monthly folders. This process is repetitive, time-consuming, and prone to human error.

## Solution
This project automates the complete document organization process using n8n and AI.

The workflow:
- Detects new Outlook emails with attachments
- Downloads the attached Excel file
- Uses AI to identify the correct month/period from the filename
- Creates the relevant folder in OneDrive
- Uploads the file automatically into the correct folder

## Business Impact
- Reduces manual document handling time by over 90%
- Improves file organization and consistency
- Minimizes human error
- Helps finance teams maintain structured monthly records

## Tech Stack
- n8n
- Outlook
- OpenAI
- OneDrive

## Status
Portfolio project completed and being documented.
