
# ALAB 318.2.1: Building an Express Application

<div align="center">
<img width="700" alt="image" src="assets/NACHA.gif">
</div>


## Introduction

Nacha, the national clearinghouse overseeing electronic money movement, reported a 4.8% increase in the volume of transactions through the ACH Network in the past year, reaching 31.5 billion payments compared to 2022. The total value of these transactions also rose by 4.4% to $80.1 trillion, as stated in a press release from Nacha on Wednesday.<br>

With the availability of Same Day ACH, which facilitated the transfer of $1.2 trillion in the first half of 2023, the modern ACH Network has become increasingly prominent in B2B payments. However, despite its growing popularity, there remain hurdles for small and medium-sized companies, particularly due to the lack of their own network payment systems.<br>

To address this issue, a proposed solution is to enable small businesses to download the Nacha file and upload their own files for ACH transactions. This would help reduce barriers to entry and participation in the ACH Network, making it more accessible to businesses of varying sizes.<br>

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

>a) First, ensure to create views and folders in my project directory.<br>
>b) Create an index.ejs file inside the views folder.<br>
>c) Once app.js was set up with code and the Express application was running, pushed all the code to the git hub. 

## License

[MIT](https://choosealicense.com/licenses/mit/)
