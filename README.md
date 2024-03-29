# Azure Calculator

The Echopath Calculator is a web application tool that allows the users to estimate the cost of using various Microsoft Azure services. It enables estimators to plan the Azure usage of their prospect / customers, by providing pricing details based on factors such as service type, region, usage volume, and specific configurations. The estimator can input their prospect's / customer's requirements and preferences into the calculator to receive an estimate of the associated costs, helping them make informed decisions about resource allocation and budgeting for their prospect's / customer's Azure projects.

---
## Requirements

For development, you will only need Node.js and a node global package, Yarn, installed in your environement.

### Node
- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v18.10.0

    $ npm --version
    v8.19.2

If you need to update `npm`, you can make it using `npm`! After running the following command, just open again the command line check.

    $ npm install npm -g

###
### Yarn installation
  After installing node, this project will need yarn too, so just run the following command.

      $ npm install -g yarn

---

### MongoDB Installation Guide

## Step 1: Download MongoDB
- Go to the official MongoDB website here and download the appropriate version for your operating system.
## Step 2: Install MongoDB

## For Windows:

- Run the downloaded installer file (.msi).
- Follow the installation wizard instructions.
- Make sure to select the option to install MongoDB Compass, a graphical user interface for MongoDB.
  
## For macOS:

- Open the downloaded .tgz file.
- Drag the MongoDB application to your Applications folder.
- You may need to update your PATH environment variable to include the MongoDB binaries. You can do this by adding the following line to your shell profile (e.g., ~/.bash_profile, ~/.bashrc, ~/.zshrc):
    $ export PATH="/usr/local/mongodb/bin:$PATH"
## For Linux:

- Extract the downloaded .tgz file to a location on your machine.
- Open terminal and paste
$ tar -zxvf mongodb-<version>.tgz
- Move the extracted directory to a desired location.
$ mv mongodb-<version> /usr/local/mongodb
- Add the MongoDB binaries to your PATH environment variable. You can do this by adding the following line to your shell profile (e.g., ~/.bash_profile, ~/.bashrc, ~/.zshrc):
export PATH="/usr/local/mongodb/bin:$PATH"
## Step 3: Start MongoDB
- Open a terminal or command prompt.
- Run the following command to start the MongoDB server:
$ mongod
- If you want MongoDB to store data in a specific directory, specify the data directory using the --dbpath option:
$ mongod --dbpath /path/to/data/directory
## Step 4: Verify Installation
- Open another terminal or command prompt.
- Run the MongoDB shell by typing:
$ mongo
- You should see the MongoDB shell prompt, indicating that you've successfully installed MongoDB.
## Additional Resources
- MongoDB Documentation: https://docs.mongodb.com/
- MongoDB Compass: https://www.mongodb.com/products/compass

---

## Install

    $ git clone https://github.com/YOUR_USERNAME/PROJECT_TITLE
    $ cd PROJECT_TITLE
    $ yarn install

## Configure app

- Create `azure_calculator/.env` file then edit it with the settings given on mail.

    
- A setting;
- Another setting;
- One more setting;

## Seeding Data 

    $ node seed.js

## Cron job runner


## Running the project

    $ yarn start

## Simple build for production

    $ yarn build
