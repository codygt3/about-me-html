# WEEK 1 HTML INTRO

## About you page!

Welcome to week one! We will introduce the basics of HTML and a little preview of CSS.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Project Structure](#project-structure)
- [Step-by-Step Guide](#step-by-step-guide)
  - [1. Create the HTML File](#1-create-the-html-file)
  - [2. Create the CSS File](#2-create-the-css-file)
  - [3. Create the JavaScript File](#3-create-the-javascript-file)
  - [4. Link the CSS and JavaScript Files](#4-link-the-css-and-javascript-files)
  - [5. Open the HTML File in a Browser](#5-open-the-html-file-in-a-browser)
- [Things to Look Out For](#things-to-look-out-for)
- [Conclusion](#conclusion)

## Introduction

In this tutorial you will learn how to make a About You page using HTML and a preview of CSS.

## Step-by-Step Guide

### 1. Create the HTML File

Open your code editor and create a file named `index.html`. Add the following code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>All About Me</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  Hello World!
  <script src="script.js"></script>
</body>
</html>
```

### 1B
Inside the <body></body> tag, use <h1></h1> to put your name!

It should look like this:
```
<body>
  <h1>My name is Katelyn</h1>
  <script src="script.js"></script>
</body>
```

### 1C
To make a sub header we will create another tag called h2 
Write down the school you go to under it.

It should look like this:

```
<body>
  <h1>My name is Katelyn</h1>
  <h2>I go to University of Hawaii At Manoa</h2>
  <script src="script.js"></script>
</body>
```

### 1D

Now create a paragraph about yourself! Talk about your favorite food, your favorite animal and why you joined this class!
You will put this under a <p></p> 

It should look like this:

```
<body>
  <h1>My name is Katelyn</h1>
  <h2>I go to University of Hawaii At Manoa</h2>
  <p>My favorite type of food is seafood! I love crab, lobster rolls and especially sushi! My favorite animal is a giraffe and a husky. I joined this class because it is super fun!</p>
  <script src="script.js"></script>
</body>
```

### 2 Add an image

Add an image of your favorite animal. you are going to put <img src=" "/> and in the quotation marks copy and paste a link of an image of your favorite animal. 

```
<body>
  <h1>My name is Katelyn</h1>
  <h2>I go to University of Hawaii At Manoa</h2>
  <p>My favorite type of food is seafood! I love crab, lobster rolls and especially sushi! My favorite animal is a giraffe and a husky. I joined this class because it is super fun!</p>
  <img src="https://www.google.com/imgres?q=giraffe%20animal&imgurl=https%3A%2F%2Flionhabitatranch.org%2Fwp-content%2Fuploads%2F2023%2F09%2FMeet-Ozzie-2.jpg&imgrefurl=https%3A%2F%2Flionhabitatranch.org%2Fanimals%2Fmeet-ozzie-the-giraffe%2F&docid=zEYiYylsmA5eRM&tbnid=5mxxKuPd_n-L5M&vet=12ahUKEwjQurKTpueJAxXiMzQIHbsCAF0QM3oECFkQAA..i&w=900&h=1200&hcb=2&ved=2ahUKEwjQurKTpueJAxXiMzQIHbsCAF0QM3oECFkQAA"/>
  <script src="script.js"></script>
</body>
```

### 2. Create the CSS File

Create a file named `styles.css` and add the following code to style your webpage:

```css
picturesize {
  width: 25px;
  height: 25px;
}
```
This adjusts the pixel size of the animal image

### 2b. Size image
Go back to your index.html file and add "className="picturesize"" before the 'src'.

```
<img className="picturesize" src="https://www.google.com/imgres?q=giraffe%20animal&imgurl=https%3A%2F%2Flionhabitatranch.org%2Fwp-content%2Fuploads%2F2023%2F09%2FMeet-Ozzie-2.jpg&imgrefurl=https%3A%2F%2Flionhabitatranch.org%2Fanimals%2Fmeet-ozzie-the-giraffe%2F&docid=zEYiYylsmA5eRM&tbnid=5mxxKuPd_n-L5M&vet=12ahUKEwjQurKTpueJAxXiMzQIHbsCAF0QM3oECFkQAA..i&w=900&h=1200&hcb=2&ved=2ahUKEwjQurKTpueJAxXiMzQIHbsCAF0QM3oECFkQAA"/>
```



## Stretch Goals
If you finish early, feel free to add images of your favorite food to your website!
Make sure to size it the same as your other picture using CSS

## Conclusion

Congratulations! You've created a simple website using HTML and a little bit of CSS. This is just the beginning – there are many more features and technologies to explore. Keep learning and experimenting to build more complex and dynamic websites.

Feel free to reach out if you have any questions or feedback. Happy coding!
