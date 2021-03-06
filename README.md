# Weather Application

[Progressive Web Applications (PWA)](https://developers.google.com/web/progressive-web-apps/) are re-defining web user experience just like native applications, with offline, notification support etc.

Vue.JS is being one of the primary frameworks driving web experience into next level with PWA.

This repository includes source for a simple weather application to illustrate how easy it is to created PWA by using Vue.js.

## Weather Application Features

- Ability to view hourly and daily weather forecast for given city
- Ability to select city based on current location
- Ability to save favourite city (with offline capability)
- Offline ability to view UI and weather data
- Ability to show offline status


![weather web app](./public/img/app-screen.PNG)

## Tools & APIs

### Web Frameworks & Plug-ins

- [Vue.js](https://vuejs.org/) - The Progressive
  JavaScript Framework
- [Vuetify](https://vuetifyjs.com/en/) - Material design component framework
- [Veutify Material Dashboard](https://www.creative-tim.com/product/vuetify-material-dashboard) - Boilarplate code for dashboard based on Vuetify
- [Vue CLI PWA](https://naturaily.com/blog/pwa-vue-cli-3) - PWA Plug-in.
- [Axios](https://github.com/axios/axios) - Promised based http client.

### Web API's / SDK's

- [Open Weather Web Api](https://openweathermap.org/api) - Free web api providing weather forecast data in json format.
- [Cors-anywhere](https://cors-anywhere.herokuapp.com) - Global proxy to support CORS.
- [HERE Maps API](https://developer.here.com/documentation/maps/topics/overview.html) - Map api for reverse geo code look-up.
- [Firebase JavaScript SDK](https://firebase.google.com/docs/web/setup) - Software Developer Kit for firebase.

### Recommended Tools

- [Vue CLI](https://cli.vuejs.org/) - Standard tooling for Vue.js Development
- [Yarn](https://yarnpkg.com/en/) - Package management
- [Visual Studio Code](https://code.visualstudio.com/) - IDE
- [Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools/) - Browser based developer tools.

### Storage

- [Firebase Database](https://firebase.google.com/docs/database) - Realtime database from google cloud enables syncing across devices.
- [HTML5 Web Storage](https://www.w3schools.com/html/html5_webstorage.asp) - Browser local storage to store offline data.

## Getting Started

### Install

Open command prompt and navigate to the directory where the above source is cloned.

Run the following command to install required packages:

    yarn install


### Run in Local Environment

Run the following command to run the application in local development server

    yarn serve

Open the application in browser: http://localhost:8080.

### Build Production Output

Run the following command to build production output to be deployed in production server

    yarn build

