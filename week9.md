# Week 9
## Learning Activities & Resources
This week we were to make a new website using SASS. Due to time constraints on the assignment, I have forked the "adviceworkshop" provided by Lindsay in the tutorial to learn what I need without losing too much time.

https://github.com/lindsaymarkward/theadviceshop 

Node js is a requirement to run these programs. Default values in set up are suitable. 
https://nodejs.org/en 


### Installing and using Grunt
To install grunt, open th ecommand terminal and run the following command:
npm install -g grunt-cli

A .json file will be required, navigate to the project directory "cd C:....." and run 
npm init

Install grunt locally to the package:
npm install grunt --save-dev

Create a Gruntfile.js in project root directory, this will contain grunt config and task definitions.

You can run grunt by typing "grunt" in the command terminal while in the project directory. 

## Estimated time
9 hours split between this weeks topic and fixing an error another team member had on his local live server.

## Content Insights
To use SASS requires more software to run. The two options are through Github or a node package manager. 
Also requires a build tool like Grunt or Gulp and the user needs to be adept at usng and navigating the command prompt. 


### Five Server - A suitable live local server for php.
Below is the alternative extension and set up provided to the team that was having difficulties with the local server.
As mentioned in the last meeting some people had issues with the live server.

Download live server (five server) in the extensions in VS code.

Create a file called fiveserver.config.js

Add the following code

// fiveserver.config.js
module.exports = {
    php: "C:\\xampp\\php\\php.exe"
  };
 

Please note that the php: file path is the default, if you have moved it to another drive or folder, you will need to change the path.

### Career/Employability/Learning Insights
This practical is the final prac that is not directly related to the assignment.
It required the knowledge of SASS, CSS, Grunt, NPM (node package manager), scotchbox, vagrant, php, and Xampp. 
This knowledge base is considerable in how to operate and maintain websites and databases and could easily be overlooked by potential employers, 
which is why it is important to demonstrate these abilities. 

#### Definitions of requirements for prac
Variables:
-	CSS and SASS variables do differ. CSS can have different values for different elements buyt sass vairiables only have one value at a time.
-	SASS variables are imperative, meaning if I use a variable, then change its value, the earlier instance will not change. 
-	SASS variable syntax: $<variable name>:<value>;

Nesting:
-	 Sass lets you nest CSS selectors in the same way as HTML.
-	Many CSS properties have the same prefix, like font-family, font-size and font-weight or text-align, text-transform and text-overflow. With Sass you can write them as nested properties:

Mixins:
-	Mixins allow you to define styles that can be re-used throughout your stylesheet. They make it easy to avoid using non-semantic classes like. float-left, and to distribute collections of styles in libraries.
-	They can be used to encapsulate styles that can be dropped into a single style rule; they can contain style rules of their own that can be nested in other rules or included at the top level of the stylesheet; or they can just serve to modify variables.

Extend/inheritance:
-	It helps you write DRY code quickly. @extend can be very useful when used properly.
-	The @extend directive lets you share a set of CSS properties from one selector to another.
-	It allows a selector to extend the styles of another selector, essentially providing a form of sub-classing. @extend works by combining selectors into a single comma-separated selector.
