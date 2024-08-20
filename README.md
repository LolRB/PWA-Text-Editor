# PWA-Text-Editor

## Description

This is a progressive web application (PWA) text editor that allows developers to create and store notes or code snippets both online and offline. It ensures reliable retrieval of content, even without an internet connection. The application is built with modern JavaScript, Webpack, IndexedDB, and is deployable as a desktop application.

## Features

- **Offline functionality:** Content is stored in IndexedDB, allowing retrieval without an internet connection.
- **Service Worker:** Automatically caches static assets and pages for offline use.
- **Desktop Installation:** Installable as a desktop application through the browser.
- **Webpack Bundling:** JavaScript files are bundled using Webpack with plugins to generate HTML, service worker, and manifest files.
- **Next-gen JavaScript Support:** The application supports the latest JavaScript features.

## Installation

There is no installation needed. To access the website [here](https://pwa-text-editor-bcgq.onrender.com/)

## Usage

- Running the Application:

Start the application with npm run start.
Open the text editor in your browser.

- IndexedDB Storage:

Content entered in the text editor is automatically saved in IndexedDB when you click off the DOM window.
Upon reopening the editor, the content will be retrieved from IndexedDB.

- Installation:

Click on the "Install" button in the browser to download the web application as a desktop icon.

## Acknowledgements

This project was created as part of a learning exercise and may contain simplistic implementations.
