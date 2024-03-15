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

First, make sure we have Node.js and npm installed on our computer/Laptop.
```
node -v
```
```
npm -v
```

**Output**

![Screenshot from 2024-03-04 12-23-11](https://github.com/ErSachinBhati/Docsify/assets/158732178/b10654aa-bc76-47d0-b62d-279f1f969697)


If not, we can download it from official website or through terminal command.

Before you begin, make sure to install necessary dependencies to run Docsify.

```
sudo apt-get update
```
It will update the list of packages and sync them to the latest version.
Now, execute the following command in the terminal
```
sudo apt-get install nodejs
```
```
sudo apt-get install npm
```

If it has been installed or is already installed, then open our command line or terminal and run the following command to install Docsify globally:

```
npm i docsify-cli -g
```
 or
```
sudo npm install -i docsify-cli -g
```

**Output**

![image](https://github.com/ErSachinBhati/Docsify/assets/158732178/7cc7d4d4-5abc-47db-8a99-e82da9b20627)


![Screenshot from 2024-03-04 14-20-53](https://github.com/ErSachinBhati/Docsify/assets/158732178/6bfc35b1-4543-41ff-aa44-d45e1f040f4a)



# Create Documentation Files

Create a new folder for your documentation and navigate into it. Inside this folder, create your markdown files (.md) containing your documentation content.


 # Initialize Docsify

Run the following command in the terminal inside your documentation folder:

```
docsify init ./docs
```

This command creates a docs folder with necessary files and configurations.


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
**Output**

![Screenshot from 2024-03-04 13-06-09](https://github.com/ErSachinBhati/Docsify/assets/158732178/8b1dc818-387b-45af-88b8-fec7b9daa3b7)


This command starts a local development server. Open your web browser and go to http://localhost:3000. You should see your documentation.

**Output**

![Screenshot from 2024-03-04 13-18-01](https://github.com/ErSachinBhati/Docsify/assets/158732178/0c8ec1b2-e0fa-4926-b204-939a155e7f03)



# Customize

Docsify provides a simple way to customize the appearance of your documentation. You can modify the index.html file to include custom styles or themes.

**Output**

![Screenshot from 2024-03-04 16-18-11](https://github.com/ErSachinBhati/Docsify/assets/158732178/612d5276-0170-48f2-a12d-65fcb5081a75)



Congratulations! You've successfully installed Docsify, now you can check version of docsify by run following command.

```
sudo docsify -v
```


![Screenshot from 2024-03-04 18-23-37](https://github.com/ErSachinBhati/Docsify/assets/158732178/0e9310ce-7a4e-4a40-9836-d68cf25aa622)



# Deploy Documentation

After completion, you can deploy it to a web server or on GitHub.
