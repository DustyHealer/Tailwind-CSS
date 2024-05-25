# NPM Commands to work with tailwind css
Step 1 - npm install -D tailwindcss postcss autoprefixer
Step 2 - npm install vite
Step 3 - add the below code to package.json

"scripts":{
    "start": "vite"
  },

Step 4 - npx tailwindcss init -  This will create tailwind.config.js file.
Step 5 - Add the below inside the config
content: ["*"], - This will support all the content

