# This file contains the instructions on how I setup Vite in VS Code

## Note: I decided to use VS Code instead of Webstorm because
    1. Webstorm's shorcut layout is too different comapred to VS Code
    2. Settings and options etc are too deeply nested in the settings groups (it's hard to find what i need)
    3. The names of things are different to VS Code even if they do the same thing
    4. I aint got time to start re-learning how to use a new IDE
    5. I do not like the Complexity Demon

### Setting Vite up using Powershell (Via Windows Terminal App)
    1. Go to https://vitejs.dev/guide/
    2. Scroll to the "Scaffolding Your First Vite Project" section of the page
    3. Copy the command "npm create vite@latest" found in the NPM group
    4. Cd to your chosen project location that Vite will create the project folder in
    5. Paste the command into the opened PowerShell terminal
    6. Once completeed, the terminal will give you commands that you will need to follow 1 by 1
    7. The commands will be
        7.1. Cd to the project folder (the actual command will be shown by the terminal)
        7.2. npm install
        7.3. npm run dev
    8. The last command "npm run dev" will then have tyhe terminal display the link to the development server so just copy and paste that link into your browser and boom that's it for this part

### Adding Sass (SCSS) to this specific Vite project
    1. In a new PowerShell terminal, cd to the newly created Vite project
    2. Open this link https://vitejs.dev/guide/features#css-pre-processors in the broswer
    3. Navigate to the "CSS Pre-processors" section (the link should have done this already)
    4. Since SASS & SCSS are the same and SCSS is just the newer version of SASS, I will need to input the command "npm add -D sass" in the Powershell terminal that I already opened (be sure to check that you have cd'd to the Vite project's location before this)
    5. After the command is run and the terminal has confirmed it, go to your Vite project in VS Code and check the "package.json" file and confirm that the below is present

        "devDependencies": {
        "sass": "^1.77.4",
        "vite": "^5.2.0"
        }
    6. That's it!

### Importing individual SCSS files using a JS file
    1. 


            /*Positioning*/
            /*Layout*/
            /*Dimensions*/
            /*Box Model*/
            /*Font*/
            /*Animation*/
            /*Color*/
            /*Background*/
            /*Other*/
            /*Animation*/