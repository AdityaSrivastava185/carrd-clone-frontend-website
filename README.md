# carrd-clone-frontend-website
This is the clone of the frontend design from one of the template of website available at carrd.com. This is build by using html and tailwind css.
1) MAKE SURE THAT YOU ALREAFY HAVE NODE JS INSTALLED IN YOUR COMPUTER AND IF NOT THEN YPU CAN DOWNLOAD THAT FROM 👉 https://nodejs.org/en

2) YOU NEED TO SET UP TAILWIND CSS WHICH IS A CSS FRAMEWORK FROM THEIR OFFICIAL WEBSITE 👉 https://tailwindcss.com/

3) IN THIS STEP YOU HAVE TO OPEN YOUR COMMAND TERMINAL AND RUN 👉"npm init"👈 in your current folder

4) THEN YOU HAVE TO INSTALL VITE USING THE COMMAND IN THE TERMINAL 👉"npm install vite"👈 

5) GO TO "package.json" file and there inside the "script" object type 

    "start": "vite",
    
    "build":"vite build"
    
    and save the file
    
6) ADD " <script src="https://cdn.tailwindcss.com"></script> "  INSIDE OF THE HEAD TAG IN index.html PAGE

7) THEN RUN THESE COMMANDS ONE BY ONE IN THE TERMINAL 

    👉 npm install -D tailwindcss postcss autoprefixer👈
    
    👉npx tailwindcss init👈

8) INSIDE "tailwind.config.js" file in your code editor update

👉/** @type {import('tailwindcss').Config} */

    module.exports = {

     content: ["*"], 
  
        theme: { 
  
        extend: {},    
      },  
     plugins: [],  
  
    }👈

9) THEN RUN THE COMMAND IN THE TERMINAL "npm run start" AND THIS WILL OPEN YOUR LOCALHOST
