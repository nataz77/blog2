# Almdev Blog

## Installation
Fire up your terminal, go to the new folder and run:
```
npm install
```
Now you are good to go.

## Build it for dev
To build your static website for local development run:
```
npm run build-dev
```
This will build the static website into the `/dev` folder without all the minifiying and purging stuff (<- much faster and a more human friendly code output, but a much bigger package)

## Run in dev mode
To run the build-dev task automatically on file changes run:
```
npm run watch
```
That will run a local server from `/dev` folder and connects browser sync to it. On changes within the `/src` folder it will run the `npm run build-dev` command automatically and will refresh your browser.

## Build it for prod
If you are done with your dev work and happy with it its time to deploy your static website into the wild wild west (www). To build your static website for a prod deployment run:
```
npm run build
```
That will output the full site, with purged and minified CSS and minified html. The output will be stored in the `/public` folder.
