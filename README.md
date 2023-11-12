# <Creating README Generator: Week-9-Challenge (Node.js)>

## Table of Contents
 1. [Description](#description)
 2. [Technologies Used](#technologies-used)
 3. [Installation](#installation)
 4. [Features](#features)

## Description

This application was created using node.js to generate professional README.md docs from the command line, and aims to cut down on the amount of time developers are using to write their README.md files. This way more of their time can be devoted to creating, maintaining, and updating their applications. By the use of inquirer (node package manager) this application takes the user through a series of prompts, asking them their name, title of their application, application description, installation instructions, usage information, contribution guidelines, test instructions, what type of license they want their application to be covered under, as well as their GitHub handle, and primary email. Once all prompts are answered, the application generates a professional README.md markdown file with the users inputs. This was the first application I have created using a backend technology (node.js), and gave me greater insight into the way back end developers problem solve without the use of a user interface or live browser. Through building this application I learned how to import the libraries inquirer and file system into a node application, the use of prompts within the command line, template literals and arrow functions (ES6 syntax), and continued to build on all previous programming knowledge I have gained so far (for this application, mainly the utilization of conditionals statements).

## Video Walkthrough

https://drive.google.com/file/d/1nUfQbtFsdXHdMTetCuJtYdThdO6zbyXW/view

## Technologies Used

This project is powered by Node.js v16, and utilizes the inquirer v8.2.4 (node package manager), and file system module (node package manager).

## installation

Clone the repo: git clone https://github.com/Donsidious/README-Generator

Open in VS Code. If you do not have VS code you must install it.

Using the terminal, install node.js v16. If you have homebrew, the command should look like the following (brew install node@16), however this may vary and the documentation should be consulted.

Once node.js v16 is installed, in the terminal, utilize the command npm init -y to initialize and create a package where project files will be stored.

Next, use the terminal to run the command npm i inquirer@8.2.4 to install v8.2.4 of the inquirer.

To run the application, within the terminal, type the command node index.js.


## Features

This application enables users to effortlessly create professional README.md documents through command-line interaction. Users provide project details by responding to prompts, which are then used to generate a README.md file. Notable features include an automatically added licensing badge, a user-friendly table of contents with clickable links, and a 'Questions' section with links to the author's GitHub profile and email for easy contact.

