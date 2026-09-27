# LifePilot

LifePilot is a local-first organizer for documents and reminders. It runs without an account, API key, database, or cloud service.

## Run

Requirements: Node.js 20.9 or newer.

```bash
npm install
npm run dev
```

Open http://localhost:3000. No `.env` file or external service setup is required.

## Features

- Add PDF, JPG, JPEG, PNG, or WEBP files up to 8 MB
- Keep original files in browser IndexedDB
- Manually record document details, dates, amounts, and reference numbers
- Create and complete reminders
- Search and filter the document library
- Delete a document and its locally stored file
- Delete all local workspace data in Settings

## Storage and limitations

Files are stored in the current browser on the current device. Workspace details and reminders use browser local storage. There is no account, cloud sync, automated OCR, AI extraction, email, or push notification service. Browser site-data cleanup can delete this workspace, so keep separate copies of important documents.

The app is intended to help organize personal paperwork. Verify dates and other important details against the original documents.
