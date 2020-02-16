This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) and modified with scripts for building and uploading for [darklang](https://darklang.com).

## Clone the repo
`git clone git@github.com:aashanand/react-dark-starter.git`

## Set Environment Variables

To start, first set up some environment variables.

`export DARK_STATIC_ASSETS_BASE_URL='replace-with-your-canvas-name';`
`export DARK_USERNAME='replace-with-your-dark-username';`
`export DARK_PASSWORD='replace-with-your-dark-password';`

Then, there are just four more steps before you're in business.

## Installing modules

`npm install`

## Special build command

`npm run build-for-dark`

## Get Dark CLI
You only need to do this once per project. Every other time, you can skip to the next step.

`npm run get-dark-cli`

## Deploy to Dark

`npm run deploy`

If you get "Not Found" on this step, you need to visit [https://darklang.com/a/USERNAME-CANVASNAME](https://darklang.com/a/USERNAME-CANVASNAME) first in your browser.

That's it! Go to your dark canvas and follow the 404s into backend development.
