
# figjam-create-sticky

<!-- ![alt text](https://github.com/destefanis/auto-theme/blob/master/assets/Auto%20Theme%20Art.png?raw=true "Auto Theme Cover Art") -->

A Figjam plugin for converting text layers and paragraphs into sticky notes.

## How to run locally
* Run `yarn` to install dependencies.
* Run `yarn build:watch` to start webpack in watch mode.

⭐ To change the UI of your plugin (the react code), start editing [App.tsx](./src/app/components/App.tsx). 
⭐ To interact with the Figma API edit [controller.ts](./src/plugin/controller.ts).  
⭐ Read more on the [Figma API Overview](https://www.figma.com/plugin-docs/api/api-overview/).

## This is a public plugin, you'll be able to install it from Figma community

## How to use this plugin locally
* Follow the instructions for running locally
* In Figma, create a plugin and select this Auto Theme plugin manifest file.
* Upload the plugin images from the asset directory, then hit publish internally.

## How it works
* When a frame or multiple frames are selected the code loops through each layer.
* More coming soon.

## Toolings
This repo is using:
* React + Webpack
* TypeScript
* TSLint
* Prettier precommit hook
