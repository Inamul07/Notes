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
12. If you are creating a component keep the name starting with an uppercase letter 
    - So react knoes that it is a component
- **Note:** The file `index.html` contains a div with id `root`.
    - This div contains the app (i.e) The app lives in that div
13. To render it to `index.html` import `ReactDom`
    - `import ReactDom from 'react-dom'`
14. Now add the code `ReactDom.render(<ComponentName/>,document.getElementById('root'));`
15. Use ES7 extension for better programming
    - ![ES7extension](Images/ES7extension.png)
    - (i.e) If you type `rfce` it will type the code component
    - ![rfceCode](Images/rfce.png)
16. Always enclose your app in a function and write your component code in the return statement (COMPULSORY)
    - ![ComponentImage](Images/Component.bmp)
17. Use paranthesis in the return statement
    - The HTML tags inside the return statements are called `JSX`
18. Use can use only one parent tag and it may contain many tags inside it
    - You can use `<React.Fragment>` tag or an empty tag `<>` to enclose the remaining tags
    - Or you can use tags like `<section> , <article>` e.t.c for understanding
19. Always use camelCase for html attributes
    - For e.g for class type `className`
