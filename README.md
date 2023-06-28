# JATE - Just Another Text Editor

## Description

```
This is a text editor single-page application that runs in a browser, that meets the PWA criteria.
The start code was already given, added some features like data persistence techniques, methods that
are useful for storing and retrieving data. App used a package called `idb`, which is a lightweight
wrapper around the IndexedDB API and the application works on offline.
```

## Table Contents

- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Deployed Link](#deployed-link)
- [Usage](#Usage)
- [Installation](#Installation)
- [ScreenShots](#ScreenShots)
- [Resources](#Resources)

## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent
pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Deployed Link

[The link for my deployed application can viewed here](https://pwa-texteditor-app-f0a03820e591.herokuapp.com/)

## Usage

Open the terminal and run this code `npm run start`

## Installation

- `git clone` the repo to the local machine.
- `npm install` to install all the dependencies
- `npm run star` to run npm run build and server and node server.js

## ScreenShots

The following are some of the screenshots

![Index](./images/index.PNG)

IndexDB

![Database](./images/db.PNG)

Manifest

![Manifest](./images/manifest.PNG)

Service Worker

![Service worker](./images/sw.PNG)

## Resources

- Course Materials
