Project Installation Guide - Deployed Project link - https://devrazorpayclonex.netlify.app/

Step 1 - Donwload and install Nodejs from here (Official Website) (if already installed skip this step)- https://nodejs.org/en 	

Step 2 - Download our project's zip file - link - https://github.com/17Ved/tailwindcssrazor

Step 3 - Create a folder on desktop, Right click on folder and click on 'Open with VSCode'.

Step 4 - Install all necessary dependencies - by following below commands
			
			I.   Press - Ctrl + Shift + `   --> to open new terminal.
						 OR - Click on terminal tab -> new terminal.

			II.  Run Commands - 
					1. npm install -D tailwindcss postcss autoprefixer vite

					2. npx tailwindcss init -p
			
			III. Install tailwind css 'intellisense' extension from vs code.

			IV.  Go to tailwind.config.js file and add - ["*"] in content / add asterisk with double inverted comma.

			V.   Go to package.json - and add this line -  "scripts": {
    										    "start": "vite"
  										   },

  			VI.  Create 'main.css' file in same folder and add these lines - @tailwind base;
											 @tailwind components;
											 @tailwind utilities;

			VII. Now link 'index.html' with 'main.css' by inserting this line - <link rel="stylesheet" href="main.css" />	in index.html.


			VII. Optional Step - install feather icons if they're not working - using - npm install feather-icons
