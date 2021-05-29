# MIHgram(Instagram-Clone) using React & Firebase
1. Installed react modules
		  `npx create-react-app mihgram`
1. Installed firebase tools (and completed setting-up the App)
		  `npm install -g firebase-tools`
1. Started the server in port 3000 in the react folder(i.e mihgram)
		```$ cd mihgram
		$ npm start```
1. Deleted unwanted files (like logo.png)
1. Added Instagram logo
		  ```
      <img
			  className="app_headerImage"
			  src="https://www.instagram.com/static/images/web/mobile_nav_type_logo.png/735145cfe0a4.png"
			  alt="" 
		  />
      ```
1. When resizing the window to avoid extending the image we need to maintain the aspect ratio
		  `object-fit:contain;` (in CSS)
1. Added aheader for the logo
1. Now created post.js and post.css to create posts
	  1. Remember to seperate components as much as possible
1. Import everything to App.js
1. use { } to attach a js line
	 For eg: consider name as a variable
	 so use `{ name }` to use it
1. Install Material-UI
1. Took avatar and imported it from material-UI
