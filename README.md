# Introduction

Docsify is a lightweight documentation generator that allows you to create beautiful and easily maintainable documentation websites using Markdown files. It is designed to be simple, customizable, and doesn't require a complex setup.

# Characteristics

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

![Screenshot from 2024-03-04 12-23-11](https://github.com/ErSachinBhati/ErSachinBhati/assets/158732178/e16e7b16-c6a6-4877-aef3-f671e8ba7572)


If not, we can download it from official website or through terminal command.
```
sudo apt-get update
```
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

![image](https://github.com/ErSachinBhati/ErSachinBhati/assets/158732178/3d13c327-9684-4e1e-abf2-1ebc74f27d71)



# Create Documentation Files

Create a new folder for your documentation and navigate into it. Inside this folder, create your markdown files (.md) containing your documentation content.


 # Initialize Docsify

Run the following command in the terminal inside your documentation folder:

```
docsify init ./docs
```

This command creates a docs folder with necessary files and configurations.


![image](https://github.com/ErSachinBhati/ErSachinBhati/assets/158732178/adc132fc-6efe-4718-b1aa-9de19f843b4b)



 # Edit Documentation Content

Open the docs folder, and you'll find a file named README.md. This is the main documentation file written in Markdown. Edit this file using a text editor to add your documentation content. You can create additional Markdown files for different sections of your documentation.

![image](https://github.com/ErSachinBhati/ErSachinBhati/assets/158732178/052a8ca1-665b-4fc6-89f4-cd7e45ad5690)


# Preview Your Documentation

In the terminal, navigate to your project's root folder and run:

```
docsify serve ./docs
```

![image](https://github.com/ErSachinBhati/ErSachinBhati/assets/158732178/3e837af4-2f84-463b-914a-947a9eda4b2f)


This command starts a local development server. Open your web browser and go to http://localhost:3000. You should see your documentation.

![Screenshot from 2024-03-04 13-18-01](https://github.com/ErSachinBhati/ErSachinBhati/assets/158732178/bd5a53e6-843b-4db8-a46e-a980297012c5)


# Customize

Docsify provides a simple way to customize the appearance of your documentation. You can modify the index.html file to include custom styles or themes.

![image](https://github.com/ErSachinBhati/ErSachinBhati/assets/158732178/b6d620c9-7843-4bcc-96c0-112cb760e88d)



 # Deploy Documentation

Once you are satisfied with your documentation, you can deploy it to a web server or a hosting service of your choice.

If you want to deploy to GitHub Pages, make sure your repository is public, and run:

```
docsify gh-pages
```

This command pushes your documentation to the gh-pages branch of your repository, making it accessible through GitHub Pages.
That's it! You've now created a documentation website using Docsify. As you continue to update your Markdown files, Docsify will dynamically generate and update your documentation website.
a
