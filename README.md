# MDNotes

A lightweight, Markdown-powered note-taking application inspired by the native macOS Notes app.

MDNotes provides a clean workspace for creating, editing, organizing, and managing notes, with local data persistence and Firebase integration.

**[Live Demo](https://md-notes-414a7.web.app/)**
* email: guest@mail.ru
* password: password

---

## Features

- **Authentication** — user authentication with Firebase Authentication.
- **Note Management** — create, edit, and delete notes.
- **Auto Save** — automatically saves changes while editing, with a debounce mechanism.
- **Markdown Editor** — write notes using Markdown with EasyMDE.
- **Markdown Preview** — render formatted content, including GitHub Flavored Markdown and code blocks.
- **Search** — quickly find notes by title.
- **Local Storage** — persist notes locally using IndexedDB and Dexie.
- **Cloud Integration** — store and retrieve user notes through Firebase Firestore.
- **Responsive UI** — adaptive interface built with Mantine.
- **Progressive Web App** — installable application with PWA support and offline capabilities.
- **Theme Support** — light and dark appearance.

## Tech Stack

**Frontend**: React, TypeScript, Mantine

**Routing**: React Router

**Database**: Dexie, IndexedDB

**Backend**: Firebase Authentication, Firestore

**Editor**: EasyMDE, React Markdown

**PWA**: Vite PWA

## Getting Started

### Prerequisites

- Node.js (LTS recommended)
- npm

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/MDNotes.git
   ```

2. Navigate to the project directory:

   ```bash
   cd MDNotes
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open the application at the URL provided by Vite.


## Deployment

The project is configured for deployment using Firebase Hosting.

Build the production version:

```bash
npm run build
```

Deploy with Firebase CLI:

```bash
firebase deploy
```
