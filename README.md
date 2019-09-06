

### Install Node.js:


- [Install Node.js](https://nodejs.org/en/)

<<<<<<< HEAD
 ![NodeJS opening page](../images/nodeImg.png)
=======
 ![chapter2_Project](/images/nodeImg.png)
>>>>>>> f08c5985cddad97e2ee42a299c24366c9b32ae93
 
 After you install node.js on your local machine test it in CMD – node -v (should display the version) 
 ```html
 C:\Users\aygun>node -v         ->  v10.16.3
 ```
### Introduction to Node.js and NPM

-	Node.js is a JavaScript Runtime build on Google’s open source V8 JavaScript Engine. 
-	Node.js enables JavaScript to be run in a different environment than just the browser.
-	The V8 Engine executes the code – parse it and runs it in Node.js

 ![NodeJS and V8](../images/nodeV8.png)

### What is Node.js
![NodeJS why and when](../images/nodeWhy.png)


#### Running JavaScript Outside the Browser

-	Start interacting with node in the command line; - we are going to use the build in terminal
Type-in node  -> this will open up Node REPL  - Read-Evaluate-Print-Loop. It is very handy when we want to quickly test a JavaScript code snippet. 
To exit REPL type in .exit or Ctrl + D
Hit tab tab and you will see all the global variables that are available in Node
When you type in an underscore will give you the previous output to use.
Type in String. tab tag will give you the methods of the String class

#### Using Modules: Core Modules

-	Start a new .js file in the root directory
-	Type in some JavaScript code.
-	To run this file in the browser we would have to attach it to an html file;
but this is how we could run it in Node - 
In the Terminal -> command node and the name of the file -> node index.js

``` javascript
const hello = "Hello World";
console.log(hello);

```

-	More advanced features of Node would be reading files from the files system. 
In order to that we would need to use a Node Module – all kind of functionality is stored in Modules; in this case it would be the fs module (file stream). 
To make use of these modules we require them into our code and then store the result of the requiring function in a variable.
const fs = require('fs');

#### Node Documentations:
https://nodejs.org/en/docs/  -> click on the version that you are using. Here you will see all the different kind of modules that you can use: 
![NodeJS why and when](../images/nodeDoc.png)
----------------------------------------

  1. What is the Title of The Man in the Taupe Blazer?
  2. What does that title mean?
  3. What languages did you see, where are they on the developer road map?
  4. What is the conclusion at the end of the article?


#### Plan for the day:

1. What is the roadmap for this week?
  1. Front-End
    - Git
    - Basic Terminal Usage
    - Learn to Research
    - Character Encodings
    - Github
    - HTML
    - CSS

2. VS-Code Familiarization
  - Terminal
    - Opened with `ctrl + \``
    - terminal/shell
    - Language is called *CLI*
  - File Explorer
    - Opened with `ctrl + b`
    - This shows you the file structure of your system
    - Folders vs. Workspace
    - You can just right click in the file explorer to add folders and files
  - Command Pallete `ctrl + p` or `ctrl + shift + p`
    - Show keyboard shortcuts `ctrl + k, ctrl + s`

3. HTML (Lesson 1: Building Your First Web Page)
  - Define HTML & CSS
  - *HTML Terms:*
    - elements
    - tags
    - attributes
    - HTML document structure
    - self closing elements
    - code validation
  - *CSS Terms:*
    - selectors
    - properties
    - values
    - type selectors
    - class selectors
    - id selectors
    - additional selectors
  - Referencing CSS
  - CSS Resets
  - Cross Browser compatibility
4. What is Github/Git?
  - VCS: Version Control System
  - DVCS: Distributed Version ontrol System
  - Git: is the VCS we are going to use
  - Git Projects (repositories)
    - Commands:
      - git init
      - git clone
      - git add
      - git commit
      - git status
      - git pull
      - git push
      - git status
  - GitHub to Git


