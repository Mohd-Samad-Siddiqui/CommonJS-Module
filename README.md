 What is a module? 
 A module is just a piece of code in a file that you can call and use from other files.
When developing a big project, it's very useful to divide our code into modules for the following reasons:
1. Code tends to be easier to maintain and less prone to errors and bugs when it's clearly organized.
2. Modules can be easily used and reused in different files and parts of our project, without needing to rewrite the same code again.

Types of Modules
----------------
As with almost everything in life, and especially in JavaScript, there are many ways for us to implement modules.
And the first way is CommonJS Module. The code is already written up there. (In the code) I'm using the 'sum function' & 'mean function'
which is in main.js and I'm resuing it to another file app.js with the help of 'module.export' keyword in main.js. For receiving those files I'm using 'require' keyword in app.js

