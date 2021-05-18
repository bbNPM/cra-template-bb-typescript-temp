# bb-typescript-temp
This repository contains folder structure in typescript

## Getting Started
These instructions will get you to build react + typescript with temp folder structure. See Installation for notes on how to build your react.js template on your are live system.

### Installation
1. Install [nodejs](https://nodejs.org/en/download/).
2. Get [npm](https://www.npmjs.com/get-npm).
3. Run the command as the `Usage`

### Usage
```
npx create-react-app example --template bb-typescript-temp
cd {YourProject}
npm start
```

### Structure
![alt text](https://github.com/BananaBb/cra-template-bb-react-temp/blob/main/typescript.structure?raw=true)

### Assets/
The assets folder contains images and global scss folder for styling. In this project architecture, I am using centralized styling with SCSS files. I am more comfortable with that.

### Components/
The components folder contains a collection of UI components like button, custom input field, modal, etc that will be shared and used across files in the project.
Each component has a test file to help us maintain them because they used widely in the project.

### Pages/
The pages folder reflects the routes of the application. Each component inside this folder has its own route.

### Utils/
The utils folder is just a place to locate some utility functions that used repeatedly in the project. Files in the utils folder should only contain some functions like date formatting, string conversion, etc.

## License
MIT © [BananaBb](https://github.com/BananaBb)