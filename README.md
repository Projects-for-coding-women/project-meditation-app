## Project Meditation App

### The goal of this project is to practice working with HTML and CSS, including sound files

We will be using HTML, CSS, icons, background images, as well as .mp3 sound files. For the more advanced version of the project that includes video and a timer, JavaScript will be used.

**Basic functionality:** we want to offer the user two options for ambient sound (rain and sea) during meditation. The user can enjoy the sound by picking one of three options of listening time (2, 5 or 10 minutes).

**Additional functionality:** the user can see a timer countdown on the screen and video background is added to the app. This will require JavaScript.

This is what the app will look like, using the icons and images in the starter code of the project (see assets folder):  

<img src="/meditation_screenshot.png" width="600" /> 

---

### For starters

1. Create a new folder on your local computer with the name: project-meditation-app
1. Track your code with Git by using `git init` in the terminal
1. Create an index.html file with the general template code
1. Create a style.css file and add this to your HTML file as `<link>` (check how to add CSS to an HTML file)
1. Make sure you have *Meditation App* as the title (this will show in the tab when your app runs in the browser)
1. For the background image, you can use the `meditation_bg.jpg` file or another photograph you like
1. The icons you need for the webpage are in the assets folder (but feel free to search for others you would like to use)
1. Build the page according to the example. You can use Flexbox to position the elements in the right place, if you know how to use it (there is a project called **flexbox-practice** in the CodeWomen repositories, if you would like to get better at using Flexbox)
1. Feel free to use Bootstrap if you also want to practise that 😊
1. Add icons to the buttons, and add hover effect for these buttons
1. When the rain button is clicked, the background should change to the rain_image.png, and when the sun button is clicked, the background should change to show the sea_image.jpg. 
1. If you want to challenge yourself, try to make the app responsive by adding media queries for mobile, tablet and desktop
1. You can run the app in the browser with LiveServer (a VSC extension)

---

### For more advanced students

1. Follow the steps in the instructions above to build the webpage
1. Use JavaScript to build a timer that starts running as soon as one of the time options is clicked, and stops when the time has expired (if you like, you can add a gentle sound as an alert, to indicate the time has run out)
1. Use JavaScript to activate an .mp3 file when one of the ambient sound buttons is clicked (there are two sound files in the sounds folder)
1. Disable the click functionality of the buttons on click (this means that once a button is clicked, it cannot be clicked again until the action is finished)
1. Make sure the background changes with the choice of the user of an ambient sound (rain or beach)
1. Change the `play` icon of the play button to a `pause` icon when the button is clicked, and change it back again when the button is clicked
1. Stop the music when the `pause` is clicked, and restart when the button is clicked again

### For graduates

1. Challenge yourself: use video as background instead of images (see video files in folder). This means that when the rain button is clicked for ambient sound, the rain video starts playing as the background instead of seeing the background image
1. Challenge yourself: create an attractive navbar with all buttons and functionality
1. Make the app fully responsive for mobile, tablet and desktop

---

## Please note:
If you want to download a project on your local machine, do not fork it but clone the repo locally, on your computer. After that, create a new repo in your own GitHub account *with exactly the same project name*, and link the local repo to the remote repo in your GitHub account (see below). Why should you clone and not fork? It will show the project as **your own project** and not a fork of someone else's project. You can use it as a project for your portfolio.

You can connect a local project to a new, empty GitHub repo [as follows](https://docs.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line). We can do this together during a CodeWomen coding session: it is very good to know this so that you can start a project locally and afterwards link it with a remote GitHub repo.

If you clone the project without forking it, you will have to change the 'remote origin' repository after cloning. Check the remote of your local project using `git remote -v`. You will probably see:  
`origin  https://github.com/CodeWomen-Barcelona/some-codewomen-project.git (fetch)`  
`origin  https://github.com/CodeWomen-Barcelona/some-codewomen-project.git (push)`

To link your local project to your own GitHub repo, you need to change the remote origin. Have a look at this article: https://devconnected.com/how-to-change-git-remote-origin/. With `git remote -v` you can again check if remote origin has been reset and now shows the name of your GitHub account.

PS: if you work for a company that has a corporate social responsibility policy and wants to support women in tech, then here is the link to the [fundraising overview of MigraCode](https://docs.google.com/spreadsheets/d/1Zs-Mmi39bcjVw2U-iEQWSHSjkb-EmET-j1WB2oJF45Q/edit#gid=0).

---
