# create-react-app legacy versions

This repo contains the output of using Create React App to generate React apps using each version of React.

## Motivation

Create React App is a useful tool for generating new React apps with sensible configuration defaults. The version of Create React App is always changing as the tool gets updated, and with these updates come different versions of the dependencies it includes. For example, Creat React App used to use React 16, and then React 17, and now React 18.

Create React App doesn't support generating apps using older versions of their react-scripts package. If you want to generate a new React app with an older version of React, you'll have to manually change the resulting `package.json` file, re-install your dependencies, and possibly tweak a few source files and test files. This is a manual process and an error prone process.

This repo contains the output of using Create React App to generate React apps using each version of React.

## Usage

If you'd like to create a new React app using React 16, for example, you can simply copy the `react-16-app` directory to a new location and then initialize your new repo with `git init`.

The same goes for any other version of React (using the `react-17-app` or `react-18-app` directories).

You can install your dependencies using `yarn install`. If you prefer to use a different package manager like npm, you can delete the `yarn.lock` file and then run `npm install` instead.
