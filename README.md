<br>
  <h1 align="center">PWA: Text Editor</h1>

![Badge](https://img.shields.io/badge/License-MIT-yellow.svg) ![JavaScript](https://img.shields.io/badge/JavaScript-red) ![Node.js](https://img.shields.io/badge/Node.js-blue) ![Express.js@4.17.1](https://img.shields.io/badge/Express@4.17.1-green) ![idb@8.0.0](https://img.shields.io/badge/idb@8.0.0-purple)

## Description

The aim of this project was to build a text editor that runs in the browser and features a number of data persistance techniques that ensures it will be supported within all browser conditions and have the ability to maintain functionality whilst offline.

For this single page progressive web application we were provided with starter code and had to then implement methods for data control via an IndexedDB database. The `idb` package (essentialy a lightweight wrapper around the IndexedDB API) was utilised to access a number of methods for storing and retrieving data.
<br>

### Brief functionality walk through:

![Functionality Walk Through](./assets)

## Table of Contents

- [Installation](#installation)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

`npm init -y`: create a package.json file
<br>
`npm install`: install dependencies

### Dependencies

`npm i idb`: lightweight wrapper around the IndexedDB API
<br>
`npm i express`

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
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Render
THEN I should have proper build scripts for a webpack application
```

## Usage

Run this application with the command:
`npm run start`

## License

The application is covered under the following license: [MIT](https://opensource.org/licenses/MIT)

## Contributing

I will not be accepting contributions to this repository at this time.
<br>

## Questions

Questions about this repository? My best point of contact is via [Email](mailto:jayastarrbaldwin@gmail.com)
<br>
If you'd like to view more of my work in GitHub, my profile is: [jayabaldwin](https://github.com/jayabaldwin)
