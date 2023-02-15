# PWA-Text-Editor
Module 19 Progressive Web Applications (PWA): Text Editor

JATE is a simple text editor app that functions both online and offline. It has a variety of persistence options to ensure data is not lost. The application looks at the IndexedDB to populate the editor, and if there is no access, it will use local storage. For use offline, this application can be downloaded to your desktop as an application.
# License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# Badges

<p>
  <img src="https://img.shields.io/badge/-Express-black" />
  <img src="https://img.shields.io/badge/-JavaScript-yellow" />
  <img src="https://img.shields.io/badge/-Heroku-teal" />
  <img src="https://img.shields.io/badge/-Node-red" />
  <img src="https://img.shields.io/badge/-Webpack-orange" />
</p>

# Table of Contents

- [License](#license)
- [Badges](#badges)
- [Screenshots](#screenshots)
- [Acceptance Criteria](#acceptance-criteria)
- [Installation and Usage](#installation-and-usage)
- [Tests](#tests)
- [Technologies Used](#technologies-used)
- [Project Link](#project-link)
- [Contributing and Questions](#contributing-and-questions)

# Screenshots
The following image shows the application retrieves the database, posting to the editor, and saving to DB:
![Screenshot (112)](https://user-images.githubusercontent.com/109984761/218158577-77a17d36-8e7a-4136-9369-b6d37aaa5e8d.png)
The following image shows the application's `manifest.json` file:
![Screenshot (113)](https://user-images.githubusercontent.com/109984761/218158575-6275c2c8-e77d-4573-a753-87366a7619aa.png)
The following image shows the application's registered `service worker`:
![Screenshot (114)](https://user-images.githubusercontent.com/109984761/218158570-f9cf4b4f-fff4-4cc5-be74-428bad048600.png)
The following image shows the application's `IndexedDB` storage:
![Screenshot (115)](https://user-images.githubusercontent.com/109984761/218158574-06fd482c-5e4b-4d5d-9562-7d4f9ccc1f07.png)

# Acceptance Criteria

- GIVEN a text editor web application
- WHEN I open my application in my editor
- THEN I should see a client server folder structure
- WHEN I run `npm run start` from the root directory
- THEN I find that my application should start up the backend and serve the client
- WHEN I run the text editor application from my terminal
- THEN I find that my JavaScript files have been bundled using webpack
- WHEN I run my webpack plugins
- THEN I find that I have a generated HTML file, service worker, and a manifest file
- WHEN I use next-gen JavaScript in my application
- THEN I find that the text editor still functions in the browser without errors
- WHEN I open the text editor
- THEN I find that IndexedDB has immediately created a database storage
- WHEN I enter content and subsequently click off of the DOM window
- THEN I find that the content in the text editor has been saved with IndexedDB
- WHEN I reopen the text editor after closing it
- THEN I find that the content in the text editor has been retrieved from our IndexedDB
- WHEN I click on the Install button
- THEN I download my web application as an icon on my desktop
- WHEN I load my web application
- THEN I should have a registered service worker using workbox
- WHEN I register a service worker
- THEN I should have my static assets pre-cached upon loading along with subsequent pages and static assets
- WHEN I deploy to Heroku
- THEN I should have proper build scripts for a webpack application

# Installation and Usage

The project was uploaded to GitHub at the following repository: 
https://github.com/cmarielorber/PWA-Text-Editor

To install the project follow these steps:

Clone the application from GitHub with:
```
git clone [link from GitHub]
```
From the root folder, install the dependencies with:
```
npm install
```
Run the app with:
```
npm run start:dev
```
# Technologies Used

- <a href="https://expressjs.com/" target="_blank">Express</a>
- <a href="https://www.javascript.com/" target="_blank">JavaScript</a>
- <a href="https://devcenter.heroku.com/articles/heroku-cli/" target="_blank">Heroku</a>
- <a href="https://nodejs.org/en/" target="_blank">Node.js</a>
- <a href="https://webpack.js.org/guides/progressive-web-application/" target="_blank">Webpack</a>

# Project Link

[PWA-Text-Editor Heroku](https://github.com/cmarielorber/NoSQL-Social-Network-API)

# Contributing and Questions

* Pull requests are welcome. 
* If you have any questions about this application, please feel free to contact me directly at: <a href="mailto: christenmlorber@gmail.com"> Gmail<img></a>.

[Top of Page](#PWA-Text-Editor)

