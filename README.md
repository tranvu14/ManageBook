# Front-End

A project about construction steel production process.

Linh Nguyen - Update on 24/11/2019

# I - Prerequisites

## 1. Install NodeJS

- Get started with Node to use everything in the JS ecosystem, including React Js. We recommend using the Node version 10.13.0
  [https://nodejs.org/en/] NodeJS

## 2. Get the command line tool

`Installed create-react-app globally by npm install -g create-react-app`

`npm create-react-app my-app`

`cd my-app`

- Or git clone project

`cd my-app`

`npm install`

`npm start`

## Available Scripts

- You will run this tool locally to package, serve, and publish your projects.
  In the project directory, you can run:

### `npm start` || `react-scripts start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## 3. Installation Redux

- Redux is available as a package on NPM for use with a module bundler or in a Node application:

`npm install --save redux`

- Let’s create our redux store. We will keep it in src/store/index.js:

```
import { createStore } from 'redux';

const store = createStore(() => {});

export default store;
```

## 4. You will see something like this:

```
Starting project at git clone : https://github.com/tranvu14/ManageBook
DevTools is running at http://localhost:3000
Opening DevTools in the browser... (click right mouse -> inspect)
```

# II - Project Structures

### 1 - Main files

The main files that you need to pay attention to are the following:

- **public** folder: Nơi chứa các ảnh, icon, css, js.
- **components** - folder: Nơi chứa các màn hình con, nhận dữ liệu từ container.
- **containers** - folder: Fetching dữ liệu từ API Truyền dữ liệu, các hàm xử lý logic sang Component.
- **actions** - folder: Nơi chứa các action từ ứng dụng gởi đến store.
- **reducer** -folder: Nơi chứa các state thay đổi.
- **store** - folder: Nơi quản lý các state, update state, lisener và subscrible.
- **saga** - folder: Nơi xử lý các action
- **App.js** - this is where it all starts. Your app will reference this file on first load. It's sort of the index.html.

### 2 - Adding other extensions for working

# Reference plugins

##Testing

###User account for testing

- ID :
- Username :
- Password :
- Token :
  . . .

## API Docs

###Please refer the api docs at

- https://github.com/tranvu14/ManageBook

# Markdown Cheatsheet

## Headers

```
# H1
## H2
### H3
#### H4
##### H5
###### H6
```

Alternatively, for H1 and H2, an underline-ish style:

```
Alt-H1
======

Alt-H2
------
```

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Redux-Sage And Material-UI

https://material-ui.com/

### Extension : ES7 React/Redux/GraphQL/React-Native snippets

https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
