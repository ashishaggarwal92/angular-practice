# Angular

- is a framework written in JS
- front-end developmet framework
- for developing single page application
- Developed by Google

NPM - Node package manager

CLI - Command Line interface

Angular JS - is oldest version and not in use now

Latest version after version 2



## Single Page application:
- it will never reload the entier page. fast


## Installation:

- Install Node, NPM and Angular CLI
- Download Node stable version. It will also install npm.
- After installing check from command line

        node -v
        npm -v

- **Install Angular CLI:**
    - Goto official anguar cli website https://angular.io/cli
    -   Run -
            
            npm install -g @angular/cli
            
            -g means we are installing globally. So we can use angular cli anywhere in our system
            
            After install run

            ng version

## Create New Angular Project:

Goto any folder where you want to create new project

        ng new application-name

        cd application-name

        ng serve

        Open VS code using :

        cmd line -> project location -> code .


For existing angular project

        ng install -- to install node modules

        ng serve --- to run the application



## Check Which Angular version from code:

    goto package.json file and check angular/common, angular/core and other library version


## Install Any Specific version of Angular

First way - We can change angular version in package.json

Second Way - goto cmd prompt

npm install -g @angular/cli@12.0.0

## Can we use 2 node js version in the same system

Use NVM(node version manager) to use multiple versionin same operating system



## Files and Folders

### package.josn

-   dependency and version

### node_modules

- library required for our project
- no change is advisable in this


### src folder

- write our code
- app folder - it is a component
- assets folder - contains images

### index.html
- first file which loads on browser
- it contain <app-root>. This load complete angular app inside index.html

### main.ts
- connect html with angular

### style.css
- write your global style

### package-lock.json
- it contains child dependency of lib exist in package.josn

### angular.json
- if we want to load other html file during start-up instead of index.html. We can change it inside this file

### tsconfig files
- 




