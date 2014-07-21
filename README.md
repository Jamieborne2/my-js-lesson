
Jamie's Lession
======================

# Installation

### On runnable.com:
Create a new node app, and from the terminal, enter or cut and paste the following commands, then press enter or return:
    
    git clone https://github.com/Jamieborne2/my-js-lesson.git spark && spark/setup.sh
    
...some text will fly by as the repository is cloned locally and the project is setup.

Great, you're set to roll!


# This is How You Format A Title

**This will format bold text**

Here is an example of how to setup a step for your lesson.  Describe the concept you want your students to learn, show them examples in code (see the javascript format markup, below), and try to describe the concept a few different ways, comparing the concept to more common situations.  Next, create a TODO step, where the student must add a piece of code to the app, for example:

**TODO 1 :** Here, create two variables in the same statement, one named `prompt` which will hold the prompt module, and one named `fs` to hold the file-system module:

This is how you format code:
```javascript
#!/usr/bin/env node

// TODO 1 : create variables for prompt and fs by calling require in each respective module:
var 
    prompt = require("prompt"),
    fs = require("fs")
    ;
```

Often after you've explain the concept, shown code examples, then given some code the student needs to add in a TODO step, the student should be able to run the app so they can see the concept in action.  Remember that if, as in the example below, you want to run the app as an executable, you'll need to ensure at the outset you've run `chmod u+x my-lesson.js` on the file to change its permissions to executable. We have already given executable permissions to the my-lesson.js files included within the lesson plan template, but you should be aware of this caveat if you delete, add, or start from scratch.  Also, remember that if you do create your own files, _if_ they are the main entry point for your app and you entend them to run as executables, you'll need to add the <a href="https://github.com/jfraboni/simple-node-app/wiki/Shebang" target="_blank">Shebang</a> for node at the top of the file.  See the top of my-lesson.js for an example.

**Run the App** Switch to the command line, and go ahead and run the app like so:
And this is how you put a box around your text:

    # ./my-lesson.js


&copy; John Fraboni 2014