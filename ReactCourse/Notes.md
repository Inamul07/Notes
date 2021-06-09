# React Crash Course
1. Prerequisites:
    1. Text Editor : Visual Studio Code
    2. Browser : Google Chrome
    3. Additional Extension : React Developer Tools
2. Install Node.js
3. Know basic terminal commands
4. Create a folder for your app and open terminal and write `npm init` and enter app name and skip the remaining
    - Always use lowercase letters for entering app name
6. Install Bootstrap 
    - `npm install bootstrap --save`
- **Note:** A folder `node_modules` with all the dependencies installed will appear
    - If you ever clone a react repo from GitHub ,If you don't see the node_modules folder just type `npm install` on your terminal
    - This will install the node_modules folder in your device
7. Install gatsby (Optional)
    - `npm install gatsby-cli -g`
8. To create react app with required modules in a folder type `npx create-react-app app_name`
9. Move to that folder `cd app_name`
10. Now you can start the development server in localhost:3000 by typing `npm start`
11. For better learning ,delete all the files from the `src` folder except `index.js` but clear the contents fron it
12. Open `index.js` and import react `import React from 'react'`
13. If you are creating a component keep the name starting with an uppercase letter 
    - So react knows that it is a component
- **Note:** The file `index.html` contains a div with id `root`.
    - This div contains the app (i.e) The app lives in that div
14. To render your component to `index.html` import `ReactDom`
    - `import ReactDom from 'react-dom'`
15. Now add the code `ReactDom.render(<ComponentName/>,document.getElementById('root'));` in your `index.js` file
16. Use ES7 extension for better programming
    - ![ES7extension](Images/ES7extension.png)
    - (i.e) If you type `rfce` it will type the code component
    - ![rfceCode](Images/rfce.png)
17. Always enclose your app in a function and write your component code in the return statement (COMPULSORY)
    - ![ComponentImage](Images/Component.bmp)
18. Use paranthesis in the return statement
    - The HTML tags inside the return statements are called `JSX`
19. Use can use only one parent tag and it may contain many tags inside it
    - You can use `<React.Fragment>` tag or an empty tag `<>` to enclose the remaining tags
    - Or you can use tags like `<section> , <article>` e.t.c for understanding
20. Always use camelCase for html attributes
    - For e.g for class type `className`
21. You can use nested components so that your code can be more understandable
    - ![NestedComponent](Images/NestedComponent.png)
