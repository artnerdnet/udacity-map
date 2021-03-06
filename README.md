# Gluten Free Map

![Desktop](http://www.artnerd.net/imgs/code-gallery/screen2.jpg)
![Mobile](http://www.artnerd.net/imgs/code-gallery/mobile-screen2.jpg)

### Description

This map has been created for the Udacity Front-End Developer Nanodegree, as a final project. It has been developed on `React` with `create-react-app`, fetching data from `Google Maps API` and `FourSquare API`.

### Project Instructions

The goal was to build single-page application using React featuring a map of an area you live in or woud like to visit. Adding additional functionality to this application, including: map markers to identify locations, a search function to easily discover these locations, and a list view to support simple browsing of all locations. It was required to implement third-party APIs that provide additional information about each of these locations.

### Run the Application
npm start 

- Clone or download this project:

    ```
    $ git clone https://github.com/artnerdnet/bcnglutenfree.git
    ```

- Once you are inside the folder, run `npm install`
- Run the development server with `npm start`

## Auth Keys
In order to run the app, you are going to need API keys from [Foursquare](https://developer.foursquare.com/) and [Google Maps](https://developers.google.com/maps/documentation/javascript/get-api-key). 

Replace them in the App.js file:

For Google Maps:
Line 43
`const googleApi = "YOUR KEY HERE"`

For FourSquare:
Lines 49 and 50
`clientSecret: "YOUR CLIENT SECRET HERE",`
 `clientID: "YOUR CLIENT ID HERE",`
 
## Service Worker
To enable the service worker, run the application in production build mode. This is included in `Create React App`:
    
```
npm run build
```

## Dependencies

#### Packages

- [Create-react-app](https://github.com/facebookincubator/create-react-app)
- [Material IO](https://www.npmjs.com/package/create-react-app)

#### API

- [Google Maps API](https://cloud.google.com/maps-platform/)
- [Foursquare API](https://developer.foursquare.com/)

#### Design

Customized designed made by me using the following tools

- [Hatchful Logos](https://hatchful.shopify.com/)
- [Freepik](https://www.freepik.com/)
- [Google Fonts](https://fonts.google.com/)
- [Material IO](https://www.npmjs.com/package/create-react-app)
- [Adobe XD](https://adobe.com/xd)
