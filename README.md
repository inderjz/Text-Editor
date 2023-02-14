# Text-Editor
  
  
  ![badge](https://img.shields.io/badge/license-mit-blue)
    

  ## Table-of-Contents

  * [Description](#description)
  * [Installation](#installation)
  * [Usage](#usage)
  
  * [License](#license)
    
  * [Contributing](#contributing)
  * [Tests](#tests)
  * [DeployedLink](#deployedlink)
  * [Questions](#questions)
  
  ## [Description](#table-of-contents)

  With or without an internet connection, the user can generate notes or code snippets in the program, and they can be safely retrieved for use at a later time. The application will continue to function properly even when there is no active internet connection thanks to the integrated service worker and Cache APIs. Even when the app is offline, the user may view previously visited sites thanks to this program.

  ## [Installation](#table-of-contents)

  This text editor require a number of methods and store data to an IndexedDB database to be builded up.

This application will require the installation of Node.js and various npm packages.

Node Package Manager (npm) is a software manager and installer which puts the modules in place so that the node project can utilize it, and also, it manages dependency conflicts intelligently and initialized using npm init. The package.json will be generated and will contains all the details of the application in which the user have inputted during the npm initialization.

This application will use the following npm packages:-

  * npm install express (express.js)
  * npm install --save-dev webpack (Webpack)
  * npm install webpack-dev-server --save-dev (webpack-dev-server)
  * npm install --save-dev webpack-pwa-manifest (WebpackPwaManifest)
  * npm install babel (Babel)
  * npm install --save-dev css-loader (CSS-loader)
  * npm install concurrently --save (run multiple commands concurrently.) (Concurrently)
  * npm npm install idb (IndexedDB)

The required modules are bundled in the package.json file and at CLI or integrated terminal type in npm run install, the modules will be installed.



 ## [Usage](#table-of-contents)

  WHEN I run `npm run start` from the root directory
    THEN I find that my application should start up the backend and serve the client
    WHEN I run the text editor application from my terminal
    THEN I find that my JavaScript files have been bundled using webpack
    WHEN I run my webpack plugins
    THEN I find that I have a generated HTML file, service worker, and a manifest file
    
   ![one 1](https://user-images.githubusercontent.com/112728880/218630967-b6223a34-d608-41d0-83fe-16e6b008b39d.png)
   
   WHEN I use next-gen JavaScript in my application
  THEN I find that the text editor still functions in the browser without errors
  WHEN I open the text editor

<img width="1415" alt="Screenshot 2023-02-13 at 7 23 39 PM" src="https://user-images.githubusercontent.com/112728880/218631235-4e5f49ad-96f3-4a46-98b5-ffeec9fb93ab.png">

THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB

![image 2](https://user-images.githubusercontent.com/112728880/218631399-be87f5fd-ce27-47d4-b8fd-3a5ebf6223f4.png)

WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets

![image 3](https://user-images.githubusercontent.com/112728880/218631526-307bd269-4119-4428-a595-058019098312.png)

WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application 

<img width="1415" alt="Screenshot 2023-02-13 at 7 23 39 PM" src="https://user-images.githubusercontent.com/112728880/218631593-6a24e336-28f7-41ba-8b25-cab5fbc6a59e.png">


  ## [License](#table-of-contents)

  The application is covered under the following license:

  
  [mit](https://choosealicense.com/licenses/mit)
    
    

  ## [Contributing](#table-of-contents)
  
  
  Thank you for your interest in helping out; however, I will not be accepting contributions from third parties.
    

  ## [Tests](#table-of-contents)

  There are no tests for this app.
  
  
   ## [DeployedLink](#table-of-contents)

https://text-editor-inderjz.herokuapp.com/


  ## [Questions](#table-of-contents)

  Please contact me using the following links:

  [GitHub](https://github.com/inderjz)

  [Email: inderjz0711@gmail.com](mailto:inderjz0711@gmail.com)






