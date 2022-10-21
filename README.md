# cli-counter-app
A basic demonstration of a counter application using nodejs. Learn to build decentralized applications with  Winston services.

Winston is your personal assistant to all things blockchain. Together we can build better decentralized tools. 

This repository is a demonstartion of how to utilize nodejs and a couple of packages to create a basic executable application that will run on `Windows`,`Mac`, and `Linux`.

The program is a very basic counter application with a menu system built utilizing the readline and pkg node modules. It was built to demonstrate how to build a basic client application.

To build the application first open your terminal and clone this repository.

```bash
git clone https://Winston-Services/cli-counter-app.git
```

You can also fork it and start creating your own application.

Now once you have it on your local machine you will want to make sure your in the directy for the application. 

> ./cli-counter-app

Inside the folder you will see only a few files.

* index.js
  -  This is our entry point and contains all the logic for our application.

* package.json and package-lock.json .gitignore
  -  These are configuration files for nodejs and git. They tell the application and system how to interepret our program for different OS's and environments.
 
* Readme.md
  -  That's this file.

* LICENSE
  - This is the license we are releasing our software under. We have released this as MIT, that means its open source so your welcome to use it, copy it, and make it your own.

## How to Compile the applications.

Option 1
---
Install the node modules and run the build command.

```bash
npm i
```
This will install the node modules that are required to make everything work for us. This command will create a folder called node_modules. I recommend if you have time look through the folder, it has a lot of packages that can help you pick up some extra skills, and tools.

```bash
npm run build
```
This command will run the build process folling the instruction in the package.json file. If you have downloaded it and not changed any settings, it should compile for 3 operating systems. Depending on your system you can now run these applications. You will find them in the `./dist/bin` folder of the application. 
