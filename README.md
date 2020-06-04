# LearningAngular
repository to learn and study Angular9 using reference online and following the book 

> Angular: Up and Running By Shyam Seshadri  
> Copyright © 2018 Shyam Seshadri. All rights reserved.

## Installation and configuration

 -  Update ```npm``` globally
    ```
    $ sudo npm cache clean -f
    $ sudo npm install -g n
    $ sudo n stable
    ```
 -  Init local folder with package.json
    ```
    $ npm init
    ```
 -  First packages install
    ```
    $ npm install typescript
    $ npm install @angular/cli
    ```
    
    To check angular installation
    ```
    $ npx ng version
    
         _                      _                 ____ _     ___
        / \   _ __   __ _ _   _| | __ _ _ __     / ___| |   |_ _|
       / △ \ | '_ \ / _` | | | | |/ _` | '__|   | |   | |    | |
      / ___ \| | | | (_| | |_| | | (_| | |      | |___| |___ | |
     /_/   \_\_| |_|\__, |\__,_|_|\__,_|_|       \____|_____|___|
                    |___/
        
    
    Angular CLI: 9.1.7
    Node: 12.16.3
    OS: linux x64
    
    Angular: undefined
    ... 
    Ivy Workspace: <error>
    
    Package                      Version
    ------------------------------------------------------
    @angular-devkit/architect    0.901.7
    @angular-devkit/core         9.1.7
    @angular-devkit/schematics   9.1.7
    @angular/cli                 9.1.7
    @schematics/angular          9.1.7
    @schematics/update           0.901.7
    rxjs                         6.5.4
    typescript                   3.9.3
    ```
    
 -  Create an Angular application i used ```stock-market``` as <application_name> 
    ```bash 
    $ ng new stock-market        
    ```
    
 -  To check if everything ok, from Angular directory 
    ```bash
    stock-market/ $ ng serve 
    ```
    
## Bug fixing
I updated my node version because too old to let Angular work