# React Crash Course
1. Prerequisites:
    1. Text Editor : Visual Studio Code
    2. Browser : Google Chrome
    3. Additional Extension : React Developer Tools
2. Install Node.js
3. Know basic terminal commands
4. Create a folder for your app and open terminal and write `npm init` and enter app name and skip the remaining
5. Install Bootstrap 
    - `npm install bootstrap --save`
- **Note:** A folder `node_modules` with all the dependencies installed will appear
    - If you ever clone a react repo from GitHub ,If you don't see the node_modules folder just type `npm install` on your terminal
    - This will install the node_modules folder in your device
6. Install gatsby (Optional)
    - `npm install gatsby-cli -g`
7. To create react app with required modules in a folder type `npx create-react-app app_name`
8. Move to that folder `cd app_name`
9. Now you can start the development server in localhost:3000 by typing `npm start`
10. For better learning ,delete all the files from the `src` folder except `index.js` but clear the contents fron it]\
11. Open `index.js` and import react `import React from 'react'`
12. Always enclose your app in a function and write your component code in the return statement
    - ![ComponentImage](Images/component.bmp)
13. If you are creating a component keep the name starting with an uppercase letter 
    - So react knoes that it is a component
- **Note:** The file `index.html` contains a div with id `root`.
    - This div contains the app (i.e) The app lives in that div
14. To render it to `index.html` import `ReactDom`
    - `import ReactDom from 'react-dom'`
15. Now add the code `ReactDom.render(<ComponentName/>,document.getElementById('root'));`