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

## ⚙️ How It Works

### Step 1 – Receive Financial Document
A financial document is sent via Microsoft Outlook with an Excel attachment.

### Step 2 – Automatic Workflow Trigger
The incoming email is automatically detected by Microsoft Outlook, which triggers the n8n automation workflow.

### Step 3 – Download the Attachment
The workflow securely downloads the attached financial document for processing.

### Step 4 – AI Document Analysis
The AI agent analyzes the filename to identify the billing period and automatically generates the appropriate monthly folder name.

### Step 5 – Organize the Document
The workflow creates the required folder in Microsoft OneDrive (if it does not already exist) and uploads the document to the correct location automatically.
