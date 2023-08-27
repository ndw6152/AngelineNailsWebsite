## Pre-reqs

1. [git](https://git-scm.com/)
2. [nvm](https://github.com/nvm-sh/nvm) to install node and npm
3. [VS Code](https://code.visualstudio.com/) and extensions for IDE
4. [Git credentials manager](https://github.com/git-ecosystem/git-credential-manager/blob/release/docs/install.md)
5. In Chrome extensions - install [React Dev Tools](https://react.dev/learn/react-developer-tools)

### Installation guide

NVM -  
`curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.4/install.sh | bash`  
`nvm install node 20.5`

check for versions:

```
git --version
nvm --version
node --version
npm --version

output:
git version 2.40.0
nvm 0.39.4
node 20.5
npm 9.8.0
```

## First start

git clone https://github.com/ndw6152/AngelineNailsWebsite.git  
nvm use 20  
npm install

open the `app folder in vscode` or cd app

### Subsequent starts

git pull  
open the app folder in vscode or cd app  
nvm use 20  
npm install

## Available Scripts

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).
Cd in the app project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

To run all tests: `npm test -- --watchAll`

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.
