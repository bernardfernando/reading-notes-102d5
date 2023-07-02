Readings
Below you will find some reading material, code samples, and some additional resources that support the topic for this class and the upcoming lecture.

Review the Submission Instructions for guidance on completing and submitting this assignment.

Reading

# Local Storage and How To Use It On Websites

## Why would a developer use local storage for a web application?

### HTML starts the process afresh

Read this again - [local storage](https://www.smashingmagazine.com/2010/10/local-storage-and-how-to-use-it/)

- _The main problem with HTTP as the main transport layer of the Web is that it is stateless. This means that when you use an application and then close it, its state will be reset the next time you open it. If you close an application on your desktop and re-open it, its most recent state is restored._
  _This is why, as a developer, you need to store the state of your interface somewhere. Normally, this is done server-side, and you would check the user name to know which state to revert to. But what if you don’t want to force people to sign up?_

_This is where local storage comes in. You would keep a key on the user’s computer and read it out when the user returns._

## What information should not be stored in local storage?

### Sensitive information such as password and personal information. READ ON.

Read [good article to read ](https://html.spec.whatwg.org/multipage/webstorage.html#introduction-15)

## Local storage can store what type of data? How would you convert it to that type before storing?

### trings. Other data have to be converted to strings - this could slow down the application. READ further

Bookmark/Skim
[“The Past, Present, and Future of Local Storage for Web Applications”](http://diveinto.html5doctor.com/storage.html)

[from sam](https://developer.mozilla.org/en-US/docs/Web/API/Window/localStorage)

[Good article for an introduction to APIs on the browser client] (https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Client-side_web_APIs/Introduction)

Application State with Local Storage API
Overview
In this class you will are going to be introduced the concept of persisting application state with local storage.

Class Outline
Code review of previous class lab assignment
Code demo
JSON
Local storage
Lab preview and prep
Learning Objectives
Students will be able to
Describe and Define
JSON syntax, structure, rules
Application state and why it is needed
Data persistence using local storage
Execute
Convert objects to and from JSON with JSON.stringify() and JSON.parse().
Save application state directly into local storage through localStorage.setItem().
Retrieve application state from local storage through localStorage.getItem().
Notes

## What is JSON?

### javascript object notation

What is data persistence?

What is local storage?

Where is local storage stored?
