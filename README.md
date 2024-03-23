* [Introduction](#Introduction)
* [Features](#Features)
* [Install Docsify](#Install-Docsify)
* [Create Documentation Files](#Create-Documentation-Files)
* [Initialize Docsify](#Initialize-Docsify)
* [Edit Documentation Content](#Edit-Documentation-Content)
* [Preview Your Documentation](#Preview-Your-Documentation)
* [Deploy Documentation](#Deploy-Documentation)
* [References](#References)

# Introduction

Docsify helps create nice websites for documentation easily. You just need to write your documentation using simple Markdown files, and Docsify takes care of turning them into a neat website. It's user-friendly, customizable, and doesn't need a lot of complicated setup.

# Features

-Simple and lightweight

-Easy Setup

-Emoji support

-Multiple themes

-Responsive Design


Here are step-by-step instructions in simple words:

# Install Docsify

First, make sure you have Node.js and npm installed on your computer/Laptop.
```
node -v
```
This command checks the installed version of Node.js

**Command Breakdown**

node : This is the command-line interface for running JavaScript code outside of a web browser. 

-v   : This is an option that stands for "version".This is useful for verifying the installed version .

```
npm -v
```
This command checks the installed version of npm(Node Package Manager)


**Output**

sachin@sachin-Inspiron-15-3567:~$ node -v
v21.6.2
sachin@sachin-Inspiron-15-3567:~$ npm -v
10.4.0
sachin@sachin-Inspiron-15-3567:~$ 


If not, you can download it from official website or through terminal command.

Before you begin, make sure to install necessary dependencies to run Docsify.

```
sudo apt-get update
```

It will update the list of packages and sync them to the latest version.

**Command Breakdown**


sudo   :  It is a way to run programs with the security privileges of another user.

apt-get:  It is a command-line tool for handling packages, or software on system.

update :  it is updating the list of available packages from the repositories.


Now, execute the following command in the terminal

```
sudo apt-get install nodejs
```

this command is used to install Node.js

```
sudo apt-get install npm
```
this command is used to install npm(Node Package Manager)


If it has been installed or is already installed, then open your terminal and run the following command to install Docsify globally:

```
 npm i docsify-cli -g
```

The command npm i docsify-cli -g is used to install the Docsify CLI (Command Line Interface) globally on your system using npm (Node Package Manager)

**Command Breakdown**

npm         : This is the Node Package Manager, which is used to manage packages and dependencies for Node.js applications

i           : This tells npm that you want to install a package.

docsify-cli : This is the name of the package you want to install.

-g          : This stands for "global", the package will be installed globally on your system.


**Output**

sachin@sachin-Inspiron-15-3567:~$ npm i docsify-cli -g

added 204 packages in 31s

17 packages are looking for funding
  run `npm fund` for details
sachin@sachin-Inspiron-15-3567:~$ 


# Create Documentation Files

Create a new folder for your documentation and navigate into it. Inside this folder, create your markdown files (.md) containing your documentation content.


 # Initialize Docsify

Run the following command in the terminal inside your documentation folder:

```
docsify init ./docs
```

This command initializes a new Docsify documentation site in the ./docs directory

**Command Breakdown**

docsify: This refers to the Docsify command-line tool.

init: This is a command provided by Docsify to initialize a new documentation site.

./docs: This specifies the directory where you want to initialize the Docsify documentation site.

**Output**

sachin@sachin-Inspiron-15-3567:~$ docsify init ./docs
Initialization succeeded! Please run docsify serve ./docs
sachin@sachin-Inspiron-15-3567:~$ 



 # Edit Documentation Content

Open the docs folder, and you'll find a file named README.md and index.html. README.md is the main documentation file written in Markdown. Edit this file using a text editor to add your documentation content. You can create additional Markdown files for different sections of your documentation.

# Preview Your Documentation

In the terminal, navigate to your project's root folder and run:

```
docsify serve ./docs
```
this command is used to serve a Docsify documentation site locally from a specific directory (./docs)

**Output**


Initialization succeeded! Please run docsify serve ./docs

sachin@sachin-Inspiron-15-3567:~$ docsify serve ./docs
(node:11476) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
(Use `node --trace-deprecation ...` to show where the warning was created)

Serving /home/sachin/docs now.
Listening at http://localhost:3000


This command starts a local development server. Open your web browser and go to http://localhost:3000. You should see your documentation.


# Customize

Docsify provides a simple way to customize the appearance of your documentation. You can modify the index.html file to include custom styles or themes.


Now you can check the version of Docsify by running the following command.

```
sudo docsify -v
```
This command is used to check the version of Docsify.

**Output**

sachin@sachin-Inspiron-15-3567:~$ sudo docsify -v
[sudo] password for sachin: 

docsify-cli version:
  4.4.4

sachin@sachin-Inspiron-15-3567:~$ 


# Deploy Documentation

Congratulations! You have successfully installed Docsify, After completion, you can deploy it to a web server or on GitHub. 

# References

https://dev.to/erikmelone/centralize-your-documentation-with-docsify-fdf

https://puresourcecode.com/tools/create-documentation-with-docsify-and-github-pages/

https://docsify.js.org/#/
