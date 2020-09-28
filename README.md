# HacktoberFest Gettysburg 2020

Welcome to our first repository of Hacktoberfest 2020!

![Hacktoberfest](src/logo.svg?raw=true "Hacktoberfest")

In this repository, we are going to make our first contribution to Hacktoberfest 2020. 

### 1. Go to the tab in the top-right corner, underneath your profile icon where it says *fork* and click on it!

### 2. Open a console, navigate to your workspace, and use the following command to download the repository:

`git clone https://github.com/TheDJZiegler/hacktoberfest-roll-call.git`

A new directory will be created on your computer

### 3. Access the repository with the command:

`cd hacktoberfest-roll-call`

### 4. Create a new branch to begin working on. Use the command:

`git checkout -b branch-name`

### 5. Create the following changes:
Make the following changes:
Create a new file in the *assets* directory and name it (github-name).js
In this file, you must include:
~~~
        export const github-username = {
            "name": "your-name",
            "gif": "url of favorite gif", // using gif link on https://giphy.com/
            "skills": "languages you know",
            "github": "https://github.com/your-github-profile-url"
        }
        export default *github-username*
~~~

For example, here is what is listed in my file, thedjziegler.js:
~~~
        export const thedjziegler = {
            "name": "Danny Z",
            "gif": "https://media.giphy.com/media/lp3GUtG2waC88/giphy.gif", // using the gif link itself
            "skills": "Java, Javascript, Python",
            "github": "https://github.com/TheDJZiegler"
        }
~~~
Don't forget to include your file in the assets/index.js file
~~~
        export * from './thedjziegler'
        
        export * from './github-name'
~~~
We are all done with our changes! 
If you want to see the results, run the following commands:

`npm install` 

`npm start`

### 6. Stage the changes in your branch: 

`git add .`

### 6. Commit your changes to the **Pull-Request**

`git commit -m "description of the changes"`

### 7. Push your changes to the **Pull-Request**

`git push origin name-of-the-repo`

### 8. Go to the main repo on GitHub, a green button will appear with:

`NEW PULL REQUEST`

Add a descriptive message that is relevant to the name of your branch

## 9. Push the button to create your first Hacktoberfest **Pull-Request** !!