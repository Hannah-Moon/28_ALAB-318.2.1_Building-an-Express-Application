
# ALAB 318.2.1: Building an Express Application

<div align="center">
<img width="700" alt="image" src="assets/NACHA.gif">
</div>


## Introduction
This lab is intended to give you time to practice what you learned, while also researching and implementing new concepts.

## Objectives
- Create an Express application.
- Implement an Express template engine.
- Implement routes with route parameters.
- Render template views.
- Implement Express middleware.
- Serve static files.
- Send files for download.


## What is an EJS template?
- "Template engine," which refers to a module that converts files into HTML format based on syntax and settings.
- "ejs" stands for "Embedded JavaScript" and refers to HTML files with JavaScript embedded within them, typically using the .ejs extension.

## How I used EJS Template? 
- Install EJS using the below command.

```rb
npm install ejs
```

- Set the view engine. This command enables the use of EJS templates.
  
```rb
app.set("view engine", "ejs");
```

## Express module and EJS templates
- I followed these steps:

>a) First, ensure to create a views and folders in my project directory.
>b) Create a index.ejs file inside the views folder.
>c) Once app.js was set up with code, and Express application was running, pushed all the code to git hub. 

## License

[MIT](https://choosealicense.com/licenses/mit/)
