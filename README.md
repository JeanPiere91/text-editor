# TEXT EDITOR
  ![HTML/CSS](https://img.shields.io/badge/CSS-blue) ![JavaScript](https://img.shields.io/badge/JavaScript-red) ![Node.js](https://img.shields.io/badge/Node.js-orange) ![Express.js@4.17.1](https://img.shields.io/badge/Express.js@4.17.1-grey) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
  ## Description
  
   My task was to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also    function offline.

   To build this text editor, I will start with an existing application and implement methods for getting and storing data to an IndexedDB database. I will use a package called `idb`, which is a lightweight wrapper around the IndexedDB API. It features a number of methods that are useful for storing and retrieving data, and is used by companies like Google and Mozilla.

   I will deploy this full-stack application to Render using the Render Deployment.
  
  ## Table of Contents
  
  - [Installation](#installation)
  
  - [Usage](#usage)
  
  - [License](#license)
  
  - [Contributing](#contributing)
  
  - [Tests](#tests)
  
  - [Questions](#questions)
  
  ## Installation
  
  To install necessary dependencies, run the following command:
  
  ```properties
  npm i
  ```  
  
  ## Usage
  
  To use, run the following command:

  ```properties
  npm run start
  ```  
  
  ## License
  
  This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/license/mit/) file for details.
  
  ## Contributing
  | Contributors                                       | Rol                | Task                                                                          |
| -------------------------------------------------- | -------------------- | ----------------------------------------------------------------------------- |
  | [Jean Piere ](https://github.com/JeanPiere91)                        | Full Stack Developer | Create Project<br>  
  
  ## Tests
  
  To use in a test environment, run the following command:
  
  ```properties
  npm run start:dev
  ```  
  
  ## Questions

  Project Link [https://github.com/JeanPiere91/text-editor](https://github.com/JeanPiere91/text-editor)

![Demonstration of the finished Module 19 Challenge being used in the browser and then installed.](./Assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished Module 19 Challenge with a manifest file in the browser.](./Assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished Module 19 Challenge with a registered service worker in the browser.](./Assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished Module 19 Challenge with a IndexedDB storage named 'jate' in the browser.](./Assets/03-idb-storage.png)

  If you have any question about the repo, open an issue or contact me directly at [jeanpiere.bellota@gmail.com](jeanpiere.bellota@gmail.com). You can find more of my work at [JeanPiere91](https://github.com/JeanPiere91)