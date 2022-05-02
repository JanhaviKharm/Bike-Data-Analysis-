<p align="center">
  <a href="https://github.com/srikanthsista/Bikelytics/tree/master/Bikelytics"><img src="https://images.ctfassets.net/p6ae3zqfb1e3/3yrGaUpEy1CGdcqVuxibpk/2447292b8bcbf3afe3a080e254c01b75/Divvy-Watson-Meet-The-Bikes-Header_2.png"width="150"></a>
</p>

<h3 align="center">Bikelytics</h3>

<p align="center">
  Bikelytics is a highly-interactive dashboard that visualizes the trends and statistics in the usage of the Divvy Bike Sharing Service in the city of Chicago. It uses a variety of charts like line charts, bar charts, scatter map, flow map, etc. to depict the overall story behind the trips recorded in the year 2021.
</p>

## Preview
Bikelytics Dashboard visualizes the following charts/graphs/maps in an attempt to answer the questions that the bike service operator may face:

1. The Overall Performance of the System in the form of important metrics - Ridership Change, Customer and Subscriber Change, and Revenue Growth/Decline. (Image 1)
2. Ridership trend for the entire year correlated with the city's weather data. (Image 1)
3. Spatio-temporal Patterns using the Flowmap.blue ([1]) (Image 2)
4. Least Popular Routes and Stations
5. Revenue Trend
6. Stations Map
7. Summarized hourly incoming and outgoing stats for the station selected in the map.
8. Ridership Trend at the selected station.
9. Station Usage with respect to type and time of the day using Heat Map.
10. Distribution of the Demographics and their trends as per the ridertype, gender, and the age-group.

To see the detailed analysis, view the [demo]() and refer to the [report]() and [slides]().

<img src="https://github.com/srikanthsista/Bikelytics/raw/913815b3a5060c2b3e0a62fc133ce33e9a812603/Bikelytics/screenshots/preview4.png" alt="Bikelytics Dashboard">

## Features

* **Customizable:** You don't need to be an expert to customize AdminKit. Our code is very readable and well documented.
* **Fully Responsive:** With mobile, tablet & desktop support it doesn't matter what device you're using. AdminKit is responsive in all browsers.
* **Cross-Browser:** Our themes are working perfectly with Chrome, Firefox, Safari, Opera, and Edge. We're working hard to support them.
* **Clean Code:** We strictly follow Bootstrap's guidelines to make your integration as easy as possible. All code is handwritten.
* **No jQuery:** AdminKit, and all third-party libraries used in the admin template, do not require jQuery as a dependency.
* **Regular Updates:** From time to time you'll receive an update containing new components, improvements, and bugfixes.

## Quick start

### Download

* Clone this repo `git clone https://github.com/adminkit/adminkit.git`
* [Download from GitHub](https://github.com/adminkit/adminkit/archive/master.zip)
* [Download from Website](https://adminkit.io/#download)

### Build tools

The theme includes a custom Webpack file, which can be used to quickly recompile and minify theme assets while developing or for deployment. You'll need to install Node.js before using Webpack.

Once Node.js is installed, run npm install to install the rest of AdminKit's dependencies. All dependencies will be downloaded to the node_modules directory.

```sh
npm install
```

Now you're ready to modify the source files and generate new dist/ files. AdminKit uses webpack-dev-server to automatically detect file changes and start a local webserver at http://localhost:8080.

```sh
npm start
```

Compile, optimize, minify and uglify all source files to dist/ folder:

```sh
npm run build
```

## CDN support

All files included in the `@adminkit/core` npm package are available over a CDN.

**CSS:**

```html
<link rel="stylesheet" href="https://unpkg.com/@adminkit/core@latest/dist/css/app.css">
```

**Javascript:**

```html
<script src="https://unpkg.com/@adminkit/core@latest/dist/js/app.js"></script>
```

## File structure
The package contains the following directories and files:

```
adminkit/
├── .babelrc
├── .eslintrc
├── .nvmrc
├── README.md
├── package.json
├── postcss.config.js
├── webpack.config.js
├── src/
│   ├── fonts/
│   ├── img/
│   ├── js/
│   │   ├── modules/
│   │   └── app.js
│   └── scss/
│       ├── 1-variables/
│       ├── 2-mixins/
│       ├── 3-components/
│       ├── 4-utilities/
│       ├── 5-vendor/
│       └── app.scss
└── dist/
    ├── css/
    │   └── app.css
    └── js/
        └── app.js
```

## Browser Support

| <img src="https://assets.adminkit.io/browsers/edge.png" alt="Edge" width="24px" height="24px" /><br/>Edge | <img src="https://assets.adminkit.io/browsers/firefox.png" alt="Firefox" width="24px" height="24px" /><br/>Firefox | <img src="https://assets.adminkit.io/browsers/chrome.png" alt="Chrome" width="24px" height="24px" /><br/>Chrome | <img src="https://assets.adminkit.io/browsers/safari.png" alt="Safari" width="24px" height="24px" /><br/>Safari | <img src="https://assets.adminkit.io/browsers/safari-ios.png" alt="iOS Safari" width="24px" height="24px" /><br/>iOS Safari |
| --------- | --------- | --------- | --------- | --------- |
| last version| last 2 versions| last 2 versions| last 2 versions| last 2 versions

## Resources

* [Demo](https://demo.adminkit.io/)
* [Website](https://adminkit.io/)
* [Documentation](https://adminkit.io/docs)
* [Support](https://adminkit.io/support/)
* [Affiliate Program](https://adminkit.io/affiliate-program)

## Bugs and feature requests

Found a bug or have a feature request? [Please open a new issue](https://github.com/adminkit/adminkit/issues/new).

## Upgrade to PRO
Get more power with AdminKit PRO, a premium variant of AdminKit, featuring hundreds of UI components, forms, tables, charts, pages, and icons.

| Free Version        | [AdminKit PRO](https://adminkit.io/pricing/) |
|---------------------|----------------------------------------------|
| 15 Demo Pages       | ✔ 45+ Demo Pages                             |
| 1 Plugin            | ✔ 10+ Plugins                                |
| 1 Color Scheme      | ✔ 3 Color Schemes                            |
|                     | ✔ All Bootstrap 5 Components                 |
|                     | ✔ Dark Mode 🌙                               |
|                     | ✔ Compact Sidebar                            |
|                     | ✔ Calendar                                   |
|                     | ✔ Advanced Forms                             |
|                     | ✔ Drag and Drop                              |
|                     | ✔ Toast Notifications                        |
|                     | ✔ WYSIWYG Editors                            |
|                     | ✔ Premium Support                            |
