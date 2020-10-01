# HacktoberFest Gettysburg 2020

Welcome to our first repository of Hacktoberfest 2020!

![Hacktoberfest](src/logo.svg?raw=true "Hacktoberfest")

Follow the directions below to 

### 1. Go to the tab in the top-right corner, underneath your profile icon where it says *fork* and click on it!

### 2. Open a console, navigate to your workspace, and use the following command to download the repository:

`git clone https://github.com/TheDJZiegler/hacktoberfest-roll-call.git`

A new directory will be created on your computer

### 3. Change directories with the command:

`cd hacktoberfest-roll-call`

### 4. Create a new branch to begin working on. Use the command:

`git checkout -b branch-name`

Substitute `branch-name' with a descriptive name for your branch.

### 5. The following changes are necessary to be an acceptable PR:
*Make the following changes:
Create a new file in the *assets* directory and name it username.js (where username is your GitHub Username)
In this file, you must include:
~~~
        export const username = {
            "name": "First Last",
            "gif": "url of favorite gif", // using gif link on https://giphy.com/
            "skills": "languages you know",
            "github": "https://github.com/your-github-profile-url"
        }
        export default username
~~~

For example, since my username is @thedjziegler, I created the file thedjziegler.js 
~~~
        export const thedjziegler = {
            "name": "Danny Ziegler",
            "gif": "https://media.giphy.com/media/lp3GUtG2waC88/giphy.gif", // using the gif link itself
            "skills": "Java, Javascript, Python",
            "github": "https://github.com/TheDJZiegler"
        }
        export default thedjziegler
~~~

Don't forget to include your file at the end of the assets/index.js file
~~~
        export * from './thedjziegler'
        
        ...
        export * from './username'
~~~

We are all done with our changes!

### 6. Stage the changes in your branch with the command: 

`git add .`

### 6. Commit your changes to the *Pull-Request* with a descriptive message using the command:

`git commit -m "my first hacktoberfest"`

### 7. Push your changes to the *Pull-Request* with the command:

`git push origin name-of-the-repo`

### 8. Go to the repository on GitHub, a green button will appear with:

`NEW PULL REQUEST`

Add a descriptive message that is relevant to the name of your branch.

This may be a good time to review the [Code of Conduct](do.co/hacktoberconduct).

## 9. Push the button to submit your first Hacktoberfest *Pull-Request* !!