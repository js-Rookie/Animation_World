                                       Animaton_World@HacktoberFest2022
                                                               

This is a fun project aimed to make your first opensource contribution and let it be happening during a hacktoberfest......           
                                                                       
Hello and welcome to Animation Nation, a  project for Hacktoberfest 2022! This site aims to showcase your talent :)

                              --------------------------Rules-----------------------

The rules are simple. You have to:

Use HTML <divs> and CSS only! No JS, and no SVGs!
Have at least one animation in your work
Please make sure that the code is indeed your own, and not copied from someone else
That's it!

How to contribute

1: Fork this repository

2:Clone your repository that you are forked
    
      git clone https://github.com/<Your github Name>/Animation_World.git
           
3: Before you make any changes, keep your fork in sync to avoid merge conflicts:

       git remote add upstream https://github.com/js-Rookie/Animation_World.git
       git pull upstream master/main

4:After adding the upstream and checking that all files are up to date, we now will create     newbranch before editing any files. There are two ways to do so:

       git checkout -b <your branch-name>
       git checkout <your branch-name>

5.Add your changes 

      git add .

6.Check your status of the changes made

     git status      

7:Commit the changes that you made 

     git commit -m "Add your message/changes you made"

8:Finally push the changes to the repository

     git push origin <your branch name>     


steps:

In the Art directory (folder), create a directory named after yourself.
Within this folder you just made, create two files, an HTML file, and a CSS file.
Link your CSS file to your HTML file.

Using only HTML and CSS (no <script> allowed!!, create a work of art! It can be as simple or as complex as you like.

  Get a screen recording of your finished work, and make a gif! Try to crop it so that it looks good as a smallish (preferably squarish) image. Save this in your directory, together with your HTML and CSS files. Static screenshots are also acceptable.

If you don't add a gif/screenshot, the website won't show your animation.
Go to the root include.js. You will see an array of objects, each one represents a work of art that someone has created. Copy an example object and paste it at the end, filling it out with your art information and links:
  
let cards = [
  {
  
    pageLink: './Art/Your Name/your_art/index.html',
    imageLink: './Art/Your Name/your_art/art.gif',
    author: 'Your Name',
    githubLink: 'Your Github Link'
  
  }
];
