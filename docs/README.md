
# [WorldWind Kilauea](https://worldwindlabs.github.io/Kilauea/)

The __worldwindlabs/Kilauea__ project is an [online viewer](https://worldwindlabs.github.io/Kilauea/)
 for Kilauea disaster response imagery.

This project is a fork of [emxsys/worldwind-react-app](https://github.com/emxsys/worldwind-react-app)
which lets you quickly build a geo-browser web application using the 
[Web WorldWind](https://worldwind.arc.nasa.gov/web) 3D globe library with 
[React](https://reactjs.org) and [Bootstrap](https://getbootstrap.com). 
Web WorldWind is an open-source [virtual globe SDK](https://github.com/NASAWorldWind/WebWorldWind) 
developed jointly by NASA and ESA. 

The worldwind-react-app project includes:

- Initializing WorldWind with 3D globes and/or 2D maps
- Configuring and managing layers and settings
- Place name searches and geocoding
- Creating placemarks
- Going to locations
- Multi-globe support
- Plus, automatic deployment to GitHub Pages (example: [emxsys/github.io/worldwind-react-app](https://emxsys.github.io/worldwind-react-app/))
 using npm or via [Travis-CI](https://travis-ci.org/emxsys/worldwind-react-app)

This project was bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

Below you will find some information on how to perform common tasks.<br>

## Setup

After cloning this project, edit the following files to customize the branding of your app:

File | Changes
-----|--------
__package.json__ | Edit the __name__, __version__ and __homepage__ properties.
__src/components/NavBar.js__ | Edit the `<a className="navbar-brand" />` element's href, logo and branding text. 
__public/index.html__ | Change the `<title/>` and `<meta name='description' />` elements.

Then run `npm install`.


## Scripts

### `npm install`
 
Installs the dependencies defined in `package.json`.


### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.


### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!


### `npm run deploy`

Deploys the app to your `gh-pages` branch.

