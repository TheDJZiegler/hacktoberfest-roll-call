# HacktoberFest 2020 @ Gettysburg College

Welcome to our first repository of Hacktoberfest 2020!

![Hacktoberfest](src/logo.svg?raw=true "Hacktoberfest")

Follow the directions below to add yourself to our **Hacktoberfest Roll Call**

**The first thing to do is make a *fork* of this repository**

### 1. Click the *fork* button in the top right corner ↗ , directly underneath the profile icon 

### 2. Open a console, navigate to your workspace, and use the following command to download the repository:

`git clone https://github.com/USERNAME/hacktoberfest-roll-call.git`

(where USERNAME is replaced with your GitHub username)

This creates a new directory on your workspace.

### 3. Change to the new directory with the command:

`cd hacktoberfest-roll-call`

### 4. Create a new branch to begin making changes. Use the command:

`git checkout -b branch-name`

Replace `branch-name` with a descriptive name for your branch.
For example: 
`git checkout -b DJ-is-here`

### 5. Add the following changes to your branch:

Create a new file in the *src/assets* directory and name it username.js (where username is your GitHub Username)

In this file, you should add:
~~~
        export const USERNAME = {
            "name": "First Last",
            "gif": "url of you favorite gif", // using gif link on https://giphy.com/
            "skills": "languages you know or want to learn more of during Hacktoberfest",
            "github": "https://github.com/USERNAME"
        }
        export default USERNAME
~~~

For example, since my username is @thedjziegler, I created a new file called `thedjziegler.js` that has the following: 
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
        export * from './USERNAME'
~~~

We are all done making changes!

### 6. Stage the changes in your branch with the command: 

`git add .`

### 6. Commit your changes to the *Pull-Request* with a descriptive message using the command:

`git commit -m "added myself to roll call"`

### 7. Push your changes to the *Pull-Request* with the command:

`git push origin branch-name`

Make sure to use the same `branch-name` as in \#4 

### 8. Go to the repository on GitHub ➡ a green button will appear saying:

🟩`NEW PULL REQUEST`🟩

Add a descriptive message that is relevant to the name of your branch.

This may be a good time to review the [Code of Conduct](do.co/hacktoberconduct).

## 9. Push the button to submit your first Hacktoberfest *Pull-Request* 🎉🎉🎉

Now go forth and contribute to the great community of open source! ✌💖😃

# Happy Hacktoberfest!
