# challenge-10
# SVG LOGO MAKER

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
# Description:
The application enables users to enter inputs into a inquirer prompt in order to generate a logo "logo.svg" file which contains the users desired results as an SVG image.

# Table of Contents:
- [Overview](#Overview)
- [The Challenge](#The-Challenge)
- [Usage Information](#Usage-Information)
- [Installation Process](#Installation-Process)
- [License](#License)
  
# Overview

# The Challenge:
Build a Node.js command-line application that takes in user inputs to generates a SVG logo and saves it as "logo.svg" file. In addition, create a walkthrough video that demonstrates its functionality and the passing of all of the tests.


# User Story
```md
AS a freelance web developer
I WANT to generate a simple logo for my projects
SO THAT I don't have to pay a graphic designer
```

# Acceptance Criteria
```md
GIVEN a command-line application that accepts user input
WHEN I am prompted for text
THEN I can enter up to three characters
WHEN I am prompted for the text color
THEN I can enter a color keyword (OR a hexadecimal number)
WHEN I am prompted for a shape
THEN I am presented with a list of shapes to choose from: circle, triangle, and square
WHEN I am prompted for the shape's color
THEN I can enter a color keyword (OR a hexadecimal number)
WHEN I have entered input for all the prompts
THEN an SVG file is created named `logo.svg`
AND the output text "Generated logo.svg" is printed in the command line
WHEN I open the `logo.svg` file in a browser
THEN I am shown a 300x200 pixel image that matches the criteria I entered
```

# Usage Instructions
1. Open the cloned repository in any source code editor e.g. Visual Studio Code.
2. Open integrated terminal on index.js
3. Enter “node index.js” in the command line
4. Through sequential order within the command line interface - the user will be presented with npm inquirer questions - the user will provide a response to each question and proceed.
5. Once completed a SVG file named "logo.svg" will be created.
6. At your discretion, you may rename the "logo.svg" file to the file name of your choice.

# Solution URL:
https://github.com/johnlott1/challenge-10

johnlott1.github.io/challenge-10


# Screenshots:
![Alt text](<Develop/pictures/Screen Shot 2024-01-09 at 2.23.52 PM.png>)
![Alt text](<Develop/pictures/Screen Shot 2024-01-09 at 2.24.27 PM.png>)
![Alt text](<Develop/pictures/Screen Shot 2024-01-09 at 2.54.55 PM.png>)
![Alt text](<Develop/pictures/Screen Shot 2024-01-09 at 2.23.14 PM.png>)

# Built With
- JavaScript
- Node.js [Version 16.18.1](https://nodejs.org/en/blog/release/v16.18.1/)
- Jest [Version 29.4.3](https://www.npmjs.com/package/jest)
- Inquirer.js: [Version 8.2.4](https://www.npmjs.com/package/inquirer/v/8.2.4)
- Visual Studio Code: [Website](https://code.visualstudio.com/)

# What I Learned
- Create an non-deployed application that invokes a “node index.js” in the command line to generate a logo and save it as a SVG file.
- Learned Jest.
