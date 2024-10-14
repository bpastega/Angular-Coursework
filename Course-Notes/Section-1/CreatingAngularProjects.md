# Creating Angular Projects

***[08/07/2024] - bpastega***

<h2>Angular CLI</h2>
The Angular CLI is a command-line interface tool that you use to initialize, develop, scaffold, and maintain Angular applications directly from a command shell. 
https://angular.dev/tools/cli

<h2>Creating a New Project</h2>
Prior to using Angular CLI, we need to use Node.js. It can be downloaded from their official website.
https://nodejs.org/pt

To download the Angular CLI, we use the following command in CMD:

```npm install -g @angular/cli```

If this command happens to return an error, use:

``` Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned ```

With angular installed, we select the directory using the
```cd``` command on CMD followed by the path to the intended directory. 

To create a new Angular project, we use
```ng new file-name```. The CMD window will prompt us to indicate whether this project will use CSS, SCSS or Sass. It will also inquire 
```Do you want to enable Server-Side Rendering (SSR) and Static Site Generation (SSG/Prerendering)?``` Select no.

In VSCode, we will be using the following Extentions 
```Angular Language Service```
and 
```Angular Essentials (Version 18)```.

To run our program, we will be using the command
```ng serve``` which can also be run through the command ```ng s```. 

