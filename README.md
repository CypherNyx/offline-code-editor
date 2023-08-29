# offline-code-editor
Progressive Web App (PWA) that functions seamlessly both online and offline. With this application, developers can create and store notes or code snippets and retrieve them whenever needed, even without an internet connection.


## Features

- Create and edit notes or code snippets with a user-friendly text editor.
- Switch between online and offline modes and the text editor still functions in the browser without errors.
- Smooth performance and offline access with a registered service worker using Workbox.
- Static assets, including HTML, service workers, and manifest files, using webpack.
- Installation of the web application onto the desktop.
- Deployed application to Heroku.

## Acceptance Criteria:

- Provide a client-server file structure that starts the backend and serves the client with npm run start.
- Bundle JavaScript files using webpack, generating HTML, service worker, and manifest files.
- Support next-gen JavaScript while maintaining functionality without errors.
- Utilize IndexedDB for immediate database storage upon opening the text editor.
- Save entered content in the text editor to IndexedDB when clicking off the DOM window.
- Retrieve stored content from IndexedDB when reopening the text editor.
- Offer an "Install" button for easy desktop icon installation.
- Implement a registered service worker with Workbox to pre-cache static assets and pages.
- Deploy the application to Heroku with proper webpack build scripts.