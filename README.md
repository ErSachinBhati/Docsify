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

![Screenshot from 2024-03-04 12-23-11](https://github.com/ErSachinBhati/Docsify/assets/158732178/b10654aa-bc76-47d0-b62d-279f1f969697)


If not, you can download it from official website or through terminal command.

Before you begin, make sure to install necessary dependencies to run Docsify.

```
sudo apt-get update
```

It will update the list of packages and sync them to the latest version.

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
 or
```
sudo npm install -i docsify-cli -g
```

The command npm i docsify-cli -g is used to install the Docsify CLI (Command Line Interface) globally on your system using npm (Node Package Manager)


**Output**


![image](https://github.com/ErSachinBhati/Docsify/assets/158732178/c949d253-5243-41d7-808b-c78dd0cf7a11)


![image](https://github.com/ErSachinBhati/Docsify/assets/158732178/7cc7d4d4-5abc-47db-8a99-e82da9b20627)


![Screenshot from 2024-03-04 14-20-53](https://github.com/ErSachinBhati/Docsify/assets/158732178/6bfc35b1-4543-41ff-aa44-d45e1f040f4a)



# Create Documentation Files

Create a new folder for your documentation and navigate into it. Inside this folder, create your markdown files (.md) containing your documentation content.


 # Initialize Docsify

Run the following command in the terminal inside your documentation folder:

```
docsify init ./docs
```

This command initializes a new Docsify documentation site in the ./docs directory

![Screenshot from 2024-02-22 12-41-40](https://github.com/ErSachinBhati/Docsify/assets/158732178/5a643e3b-432c-450f-9170-454b57c97409)



 # Edit Documentation Content

Open the docs folder, and you'll find a file named README.md and index.html. README.md is the main documentation file written in Markdown. Edit this file using a text editor to add your documentation content. You can create additional Markdown files for different sections of your documentation.

**Output**

![Screenshot from 2024-03-04 14-52-55](https://github.com/ErSachinBhati/Docsify/assets/158732178/03955d7e-5909-47c0-91d3-fab05cbd6bcc)

![Screenshot from 2024-03-04 14-28-45](https://github.com/ErSachinBhati/Docsify/assets/158732178/e41e6fed-0f80-4c23-9aa3-3eee97ef7fa2)


# Preview Your Documentation

In the terminal, navigate to your project's root folder and run:

```
docsify serve ./docs
```
this command is used to serve a Docsify documentation site locally from a specific directory (./docs)

**Output**

![Screenshot from 2024-03-04 13-06-09](https://github.com/ErSachinBhati/Docsify/assets/158732178/8b1dc818-387b-45af-88b8-fec7b9daa3b7)


This command starts a local development server. Open your web browser and go to http://localhost:3000. You should see your documentation.

**Output**

![Screenshot from 2024-03-04 13-18-01](https://github.com/ErSachinBhati/Docsify/assets/158732178/0c8ec1b2-e0fa-4926-b204-939a155e7f03)



# Customize

Docsify provides a simple way to customize the appearance of your documentation. You can modify the index.html file to include custom styles or themes.

**Output**

![Screenshot from 2024-03-04 16-18-11](https://github.com/ErSachinBhati/Docsify/assets/158732178/612d5276-0170-48f2-a12d-65fcb5081a75)



Congratulations! You have successfully installed Docsify, Now you can check the version of Docsify by running the following command.

```
sudo docsify -v
```
This command is used to check the version of Docsify


![Screenshot from 2024-03-04 18-23-37](https://github.com/ErSachinBhati/Docsify/assets/158732178/0e9310ce-7a4e-4a40-9836-d68cf25aa622)



# Deploy Documentation

After completion, you can deploy it to a web server or on GitHub. If you want to deploy it on GitHub, first you need to create an account on GitHub. If you have already created or have an existing GitHub account, you need to log in to your GitHub account.


i) after login click on 'Create New(+)' icon.


![image](https://github.com/ErSachinBhati/Docsify/assets/158732178/f8668f75-ebb3-43b2-b693-71960c9e8fdc)



ii) then click on 'new repository'

![image](https://github.com/ErSachinBhati/Docsify/assets/158732178/a74c4a5d-711d-461d-b415-28bebb9ae5ee)



iii) enter "repository name" 

![image](https://github.com/ErSachinBhati/Docsify/assets/158732178/936ef543-1a23-4fbf-a473-0ad6f485226b)



iv) now click on ' Create repository '

![image](https://github.com/ErSachinBhati/Docsify/assets/158732178/bda8f105-4ea4-46b3-9c23-d3a5b3209a77)




v) then click on 'uploading an existing file'

 ![docs](https://github.com/ErSachinBhati/Docsify/assets/158732178/6b67f3ff-96a0-4cda-b456-18bb5b566689)




vi) now you need to upload 'README.md' file by 'drag' or 'choose your files'

![Screenshot from 2024-03-09 22-01-58](https://github.com/ErSachinBhati/Docsify/assets/158732178/0b32e86a-cc0d-4ac6-9f39-247c3799657d)



vii) after upload, now click on 'Commit changes'

![Screenshot from 2024-03-09 22-02-56](https://github.com/ErSachinBhati/Docsify/assets/158732178/1ad113e7-efd6-48a3-8796-9ead972fb035)



viii) you have successfully deploy 'README.MD' file on github

![Screenshot from 2024-03-09 22-03-33](https://github.com/ErSachinBhati/Docsify/assets/158732178/eb4ec205-f2db-4425-b345-1625aa51af03)





