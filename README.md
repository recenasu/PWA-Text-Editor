# PWA-Text-Editor
A Progressive Web Application text editor

## Description
The purpose of this project is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteris and uses a number of data persistence techniques. The application will have the capability to function offline. Acceptance Criteria have been broken down into individual features (e.g. AC01). For details on the implementation, review the applicable 'Usage' section of this README.

### User Story

* AS A developer
>    -	I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

### Acceptance Criteria

>* GIVEN a text editor web application

>* AC01: Application Opens in Editor
>    -	WHEN I open my application in my editor
>    -	THEN I should see a client server folder structure

>* AC02: Application Start
>    -	WHEN I run `npm run start` from the root directory
>    -	THEN I find that my application should start up the backend and serve the client

>* AC03: Webpack Bundling
>    -	WHEN I run the text editor application from my terminal
>    -	THEN I find that my JavaScript files have been bundled using webpack

>* AC04: Webpack Plugin Implementation
>    -	WHEN I run my webpack plugins
>    -	THEN I find that I have a generated HTML file, service worker, and a manifest file

>* AC05: Application Compatibility
>    -	WHEN I use next-gen JavaScript in my application
>    -	THEN I find that the text editor still functions in the browser without errors

>* AC06: Database Initialization
>    -	WHEN I open the text editor
>    -	THEN I find that IndexedDB has immediately created a database storage

>* AC07: Save Data to Database
>    -	WHEN I enter content and subsequently click off of the DOM window
>    -	THEN I find that the content in the text editor has been saved with IndexedDB

>* AC08: Data Persistence
>    -	WHEN I reopen the text editor after closing it
>    -	THEN I find that the content in the text editor has been retrieved from our IndexedDB

>* AC09: Application Installation
>    -	WHEN I click on the Install button
>    -	THEN I download my web application as an icon on my desktop

>* AC10: Service Worker Registration
>    -	WHEN I load my web application
>    -	THEN I should have a registered service worker using workbox

>* AC11: Asset Caching
>    -	WHEN I register a service worker
>    -	THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets

>* AC12: Heroku Deployment
>    -	WHEN I deploy to Heroku
>    -	THEN I should have proper build scripts for a webpack application

## Installation

> * To access the deployed application on Heroku, open the browser and paste the following URL in the address bar, or click on the link: TBD
> * To access the project repo, open the browser and paste the following URL in the address bar, or click on the link: TBD

## Usage

>    -	To launch the application, TBD


> * The following screens show TBD

> * Screen 1
![Exhibit 1](./assets/screen1.png)

> * Screen2

![Exhibit 2](./assets/screen2.png)

> * Screen 3

![Exhibit 3](./assets/screen3.png)



## Credits

> * npm express v4.17.1 module was used for managing API routes.
> * npm mongoose v7.0.2 module was used for database connectivity.
> * refer to package.json for these and any other dependencies.

