# React Invoice Generator

Tiny app that allows you to add items and price to be displayed in a table, displaying the total price of said items. You can also delete items from the list, and export a PDF with a detail of the invoice.

Inspired by [this Twitter thread](https://twitter.com/fmontes/status/1535427477459197952).
Code on [StackBlitz](https://stackblitz.com/edit/react-31jrxv?file=src/App.js).
StackBlitz [Demo App](https://react-31jrxv.stackblitz.io).

This directory is a brief example of a [Create React App](https://github.com/facebook/create-react-app) site that can be deployed to Vercel with zero configuration.

## Dependencies Used

- [Bootstrap](https://www.npmjs.com/package/bootstrap)
- [React Bootstrap](https://www.npmjs.com/package/react-bootstrap)
- [nanoid](https://www.npmjs.com/package/nanoid)
- [jspdf](https://www.npmjs.com/package/jspdf)
- [jspdf-autotable](https://www.npmjs.com/package/jspdf-autotable)

## To Do

- [ ] Add item to list when pressing 'Enter'.

## Deploy Your Own

Deploy your own Create React App project with Vercel.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/vercel/vercel/tree/main/examples/create-react-app&template=create-react-app)

_Live Example: https://create-react-template.vercel.app/_

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes. You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode. See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.

It correctly bundles React in production mode and optimizes the build for the best performance. The build is minified and the filenames include the hashes.
