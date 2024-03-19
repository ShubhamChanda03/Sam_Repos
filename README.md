# Azure Calculator

The Echopath Calculator is a web application tool that allows the users to estimate the cost of using various Microsoft Azure services. It enables estimators to plan the Azure usage of their prospect / customers, by providing pricing details based on factors such as service type, region, usage volume, and specific configurations. The estimator can input their prospect's / customer's requirements and preferences into the calculator to receive an estimate of the associated costs, helping them make informed decisions about resource allocation and budgeting for their prospect's / customer's Azure projects.

---
## Requirements

For development, you will only need Node.js and a node global package, Yarn, installed in your environement.

### Node
- #### Node installation on Windows

  Just go on [https://nodejs.org/](https://nodejs.org/en/blog/release/v18.17.0) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --version
    v18.17.0

    $ npm --version
    v9.6.7

If you need to update `npm`, you can make it using `npm`! After running the following command, just open again the command line check.

    $ npm install npm -g

###
### Yarn installation
  After installing node, this project will need yarn too, so just run the following command.

      $ npm install -g yarn

---

## Install

    $ git clone https://github.com/YOUR_USERNAME/PROJECT_TITLE
    $ cd PROJECT_TITLE
    $ npm install

## Running the project

    $ npm start

## Simple build for production

    $ yarn build
