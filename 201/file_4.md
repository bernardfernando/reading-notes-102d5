Box model class 03



javascript

box.js

"use strict"
let points = 0;

console.log("script logged boom shacka lacka")
Check console
/* counting points  psudo code  */
 
 alert("Welcome to my questioning game")

 // Ask the user with a message //

 let user = prompt("Iam Bernard What is your name").toLowerCase();

// the response could be string, number, empty or Null
// 

while(!user){
    user = prompt("what is your name? please we cannot progress without it!")

    // falsy values 

    if (user !== "Chris")  {
        alert(" message  xxxxx ")
            }

            alert ("Hi user " + user + " Welcome to my site")
            let answer = 
}


# Arrays
Allow more than one value in a single variable
May have different data types
index starts from 0

.length - length of array (number of items in an array)   <arrayName>.length()
**.push** - add an item to the end of array
**.pop**- removs an item from the end of array
**.unshift** - add an item to the beginning of an array.  
**.shift** - removes an element from start of array

// please look into
//.spice() array
//.slice() array

//Also lookinto 'do while loop

const locations = ["france", "mexico", "spain"];


# Lab class 4   15 June 2023

## Lab: Pair Programming and Functions
Read the document in its entirety before beginning your lab.

Problem Domain
Today will be your first exercise in pair programming. You will be assigned to work with a **partner**, and the two of you will work on and extend each other’s About Me guessing game projects. Be sure to read and follow these instructions very carefully.

Instructions
Review all four sections below for today’s lab. Pair program with your assigned partner to refactor each codebase. Equally divide your lab time so that you and your partner spend the same amount of time in each other’s code. Time management is critical.

# IMPORTANT
1. How To Get Code Ready For Work
Be sure to follow these instructions VERY carefully.

# Save everything on Github  -  git push
Note: Before starting these steps, make sure that both of your repositories are ‘clean’: in other words, everything is committed and pushed so that both the remote and local versions of your projects are in sync. This will prevent potential problems later.


# Ower of the code is the Navigator and Driver
Decide whose code you will work on first. The owner of that code (who will be the Navigator) provides the link to their GitHub repo to the other member of the pair (who will be the Driver). You can send this link over Slack.

The Driver follows the link to that repo and creates a fork of the repo in GitHub like we did in class.

The Driver then goes to their fork of the repo (the URL should have the Driver’s GitHub name in it) and copies the link to that repo (the link have the Driver’s GitHub name in it and should end in .git).

Inside of the Driver’s main work directory on their laptop, make a directory with your partner’s name and then navigate (cd) into it. From there, enter the command git clone the-link-you-copied. That will create a local version of the forked repo on the Driver’s laptop.

cd into that directory and enter code . in the terminal to open all of the files in VSCode.

Start working on the code!

2. Extend and Refine
You’ll be making some edits to each other’s sites. After each bit of work is completed (in other words, after each successful modification of a single question), be sure to do an add-commit-push cycle (a-c-p) to place the code on GitHub and preserve a versioned history of your work.

# funcitons
Move the logic for all questions into functions: Today we learned about functions, and now we’ll move the logic for the individual questions into separate functions, and call those functions to run the game.

In its most basic sense, this is pretty simple and straightforward: ‘wrap’ the logic and variables for a given question with function someFuncNameYouChoose() { at the beginning, and add a closing curly brace } at the end. To make the function execute, just call it afterwards: someFuncNameYouChoose(); After completing this step the game should behave exactly as it did before. a-c-p

Update the README file: In the README file, add in the names of the Driver and Navigator and indicate that the code was worked on together. This is basic record-keeping so that you can keep up with how the code has been edited in a user-friendly format. a-c-p

3. # Push to GitHub; Make a Pull Request
Once everything is finished, and the Driver has done the last edits and pushed them to GitHub, it’s time to send the edited code to the owner (who has been in the Navigator role the whole time, of course). We do this with a GitHub feature called a **Pull Request**, which we generally refer to as a PR.

From the Driver’s repo that is a fork of the Navigator’s repo, hit the green button that says ‘Create pull request’.

Follow the remaining steps as described onscreen and as shown here: https://help.GitHub.com/articles/using-pull-requests. (These instructions for doing a pull request from a forked repo to its source are deliberately vague, to give you practice in reading through instructions, trying things out, solving problems collaboratively, and getting guidance from documentation).

The owner of the code (the Navigator) then goes to their GitHub repo for the project and accepts the pull request. After that, in terminal on their laptop, while in the game directory, enter the command ‘git pull origin main’ to retrieve the modified code from GitHub.

When everything is finished for one person’s project, submit the links for the last pull request made from the Driver to the Navigator (in both cases) in the Canvas assignment.

4. # Pair Programming Basics
In pair programming, there are two developers working on a single body of code on a single computer.
One member of the pair is the Driver, and this person will be the one doing all of the actual typing work on the laptop. The Driver will be working on the Navigator’s code by way of forking and cloning the Navigator’s repository.
The other member of the pair is the Navigator, and this person will work with only their voice and their thoughts.
**_The Navigator does not touch the keyboard, nor does the Navigator work on their laptop “on the side”. The Navigator is fully engaged with the work that the pair is doing, typically using a piece of scratch paper to sketch diagrams, take notes, or list ideas._** At most the Navigator uses their laptop to perhaps keep a copy of this assignment document open or to look up something needed to write the code, such as a reference page like MDN.
Under no circumstances does the Navigator work on any code on their laptop: for the pair programming process to be effective, both parties must be fully engaged on the code they’re working on together.
The lab time should be divided into two sections of approximately two hours each. At the halfway mark, you should swap roles and work on the other person’s code. Remember to watch the clock and determine the best point to swap roles.
In the case of an odd number of students, one group will have three members and you should rotate through three roles: Driver, Navigator, Observer. Each person should take on each role one time. You will need to be even more mindful about watching the clock to ensure that equal time is devoted to all three projects.
Stretch Goals
Work from collections of like data: Create 3 arrays, one for each of: your questions, the correct answers, and the two possible responses. (The same applies if you’ve added in any other pieces to the questions besides the most basic structure.) Replace that content in the functions by accessing the arrays.

**Make it DRY:** 
**_Reduce the yes/no questions from five functions to one function, and then use a ‘for’ loop to iterate through the arrays and call the function for each question._**

# Code review:
 Take time to explore each other’s **CSS** and talk about how it is organized and what it is doing. Make suggestions for how it can be improved. Integrate your partner’s suggestions to improve your own styling.

# Improve accessibility:
 Collaborate on achieving better scores on accessibility audits. Include a screenshot of your new audit score in your README.md file.

Resources
No additional resources available for today.

Submission Instructions
In the text box on this assignment, enter the URLs from the repos that you worked on in this format:

I was Navigator on: link-to-the-last-PR-your-partner-made
I was Driver on: link-to-the-last-PR-you-made-as-Navigator
Also, give a brief answer the following questions:

How did the pair programming process go in general?
Did you learn anything from your partner? If so, what?
What was the most difficult part of the assignment today?
What was the easiest part of the assignment today?
Anything else you’d like to share?
How long did it take you to complete this assignment? And, before you started, how long did you think it would take you to complete this assignment?
© Code Fellows 202
______


# Readings: HTML Links, JS Functions, and Intro to CSS Layout
Below you will find some reading material, code samples, and some additional resources that support the topic for this class and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

# Reading
Learn HTML
## Creating Hyperlinks
Creating a hyperlink: 

To create a basic link, we wrap text or other content inside what element?  <a>
The href attribute contains what information? <a href = "url"> link text </a>
# href contains the link to the place where when you click on it takes you. Link text does not have to be text. There could be an absolulte URL or a relative URL.

What are some ways we can ensure links on our pages are accessible to all readers? 
### By having meaningful text rather than click here so that those who are visually impared can get a feel of what has to be done and why.

## CSS Layout: It is a CSS grid layout - two dimensional layout system for the web. It allows you lay content out in rows and columns and has many features that  make building complex layouts straight forward.

CSS Layout:
Normal Flow CSS Layout: the way the Blocks and Inline elements are displayed on a page before any changes are made to their layouts. The flow is essentially a set of things that are all working together and know about each other in your layout.  Once something is taken out of low it works independently. 

Positioning

What is meant by “normal flow”?

# What are a few differences between block-level and inline elements?  
## Block level - always starts from a new line and browsers automatically add some space (a margin) before and after the elements. The always take up the full wideth available (left to right). Eg <p>, <div>, <h1> to <h6> <ul>, <ol>, <dl>, <pre>, <hr/>, <blockquote>, <address>

### Inline element: never start from a new line. spaces as bounded by the tags in the HTML element.

___ 
# positioning is the default for every html element.
position property specifies the type of positioning method used for an element.
5 different position values
- **static**: this is positioned according to the normal flow of the page, not any specific way.
- **relative**: positioned relative to its normal position. Setting the top, right, bottom and left. 
- **fixes**: stays at the same place even if scrolled
- **absolute**: relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed). If an absolute positioned element has no positioned ancestors it uses the documents body and moves along with page scrolling.
- **sticky** : this is based on users scroll position. toggles between relative and fixed.

div.static {
    position:static;
    border: 3px solid #73AD21
}


## Name a few advantages to using absolute positioning on an element.help having precise positioning.(better to use float.)

## What is a key difference between fixed positioning and absolute positioning? fixed related to the browser window; Positioned absolute to its first positioned parent.

# Learn JS
## Functions – Reusable Blocks of Code

## Describe the difference between a function declaration and a function invocation. Declation means, the method and invocation is getting it to work.
## What is the difference between a parameter and an argument? Values declared within the function when it is called are arguments, variables that are defined when the function is declared are known as parameters.

Miscellaneous
6 Reasons for Pair Programming

Pick 2 benefits to pair programming and reflect on how these benefits could help you on your coding journey.
This definitely helped. 