# Collaborative Thread Editor

This project provides a minimal client-side editor for bilingual threads (English / Russian). It uses Firebase for real-time data sync and anonymous authentication.

## Features

- Thread archive listing stored threads
- Real-time editing of posts with two columns
- Anonymous Firebase authentication
- Add or delete posts
- Export thread content for Notion (copied to clipboard)

## Setup

1. Create a Firebase project with Firestore database.
2. Enable anonymous authentication in the Firebase console.
3. Copy your Firebase configuration into `index.html` and `editor.html` where the comment `// TODO: replace with your config` appears.
4. Serve the files with any static web server or open directly if allowed.

## Usage

- Open `index.html` to see all threads and create a new one.
- When editing a thread, each post has an English and Russian column. Changes are saved instantly to Firestore.
- Use **Copy for Notion** to place the bilingual content on your clipboard.

This is a basic demonstration; additional features such as inline comments or file uploads can be added as needed.
