# WEEK 1 HTML INTRO

## About you page!

Welcome to week one! We will introduce the basics of HTML and a little preview of CSS.

## Table of Contents

- [Introduction](#introduction)
  - [1. Create the HTML File](#1-create-the-html-file)
  - [2. Create a Body and Header](#2-create-a-body-and-header)
  - [3. Sub Header](#3-sub-header)
  - [4. Make a Paragraph](#4-make-a-paragraph)
  - [5. Add an image](#5-add-an-image)
- [Now It's Time To Make It Pretty!!!](#now-its-time-to-make-it-pretty)
- [Create the CSS File](#create-the-css-file)
- [Size image](#size-image)
- [Strech Goals](#stretch-goals)
- [Conclusion](#conclusion)

## Introduction

In this tutorial you will learn how to make an 'About You' page using HTML and a preview of CSS.

HTML stands for Hypertext Markup Language. It makes the website!

CSS stands for Cascading Style Sheets. This is to make the HTML website more pretty!

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

### 2. Create a Body and Header
The body tag just organizes everything you are going to write! That is why it is called a body. Kind of like a container where the <body> is the top of the lid, and the second </body> is the base of the container. 
Inside the <body></body> tag, type inside ```<h1></h1>''' This means header 1 which is the biggest size! 
In between the header tag introduce yourself by saying 'My name is {your name}.' 

It should look like this:
```
<body>
  <h1>My name is Katelyn</h1>
  <script src="script.js"></script>
</body>
```

### 3. Sub Header
To make a sub header we will create another tag called ```<h2></h2>``` this is a header that is a little bit smaller than the first one. 
Write down a short sentence about the school you go to under it.

It should look like this:

```
<body>
  <h1>My name is Katelyn</h1>
  <h2>I go to University of Hawaii At Manoa, It is so nice!</h2>
  <script src="script.js"></script>
</body>
```

### 4. Make a Paragraph

Now create a paragraph about yourself! Talk about your favorite food, your favorite animal, your favorite hobby and why you joined this class!
You will put this under a paragraph tag ```<p></p>```

It should look like this:

```
<body>
  <h1>My name is Katelyn</h1>
  <h2>I go to University of Hawaii At Manoa</h2>
  <p>My favorite type of food is seafood! I love crab, lobster rolls and especially sushi! My favorite animal is a giraffe and a husky. I joined this class because it is super fun!</p>
  <script src="script.js"></script>
</body>
```

### 5. Add an image

Add an image of your favorite animal. you are going to put ```"<img src=" "/>"``` and in the quotation marks copy and paste a link of an image of your favorite animal. 

The best way to copy an image is to go on google, search up the animal, and then right click over the image and select 'copy image address' then paste that with Control V in the quotation marks.

```
<body>
  <h1>My name is Katelyn</h1>
  <h2>I go to University of Hawaii At Manoa</h2>
  <p>My favorite type of food is seafood! I love crab, lobster rolls and especially sushi! My favorite animal is a giraffe and a husky. I joined this class because it is super fun!</p>
  <img src="https://www.google.com/imgres?q=giraffe%20animal&imgurl=https%3A%2F%2Flionhabitatranch.org%2Fwp-content%2Fuploads%2F2023%2F09%2FMeet-Ozzie-2.jpg&imgrefurl=https%3A%2F%2Flionhabitatranch.org%2Fanimals%2Fmeet-ozzie-the-giraffe%2F&docid=zEYiYylsmA5eRM&tbnid=5mxxKuPd_n-L5M&vet=12ahUKEwjQurKTpueJAxXiMzQIHbsCAF0QM3oECFkQAA..i&w=900&h=1200&hcb=2&ved=2ahUKEwjQurKTpueJAxXiMzQIHbsCAF0QM3oECFkQAA"/>
  <script src="script.js"></script>
</body>
```

## Now It's Time To Make It Pretty!!!
### This is where we will use CSS
### Create the CSS File

Create a file named `styles.css` and add the following code to style your webpage:


we want to adjust the size of the picture on our page, so we can call this 'picturesize'
You can play around with the size but you are going to put open and closing curly braces { } and inside put 'width: ;' and 'height: ;' put whatever number you want and adjust it to your liking! make sure to put px which means pixels at the end of the number and a semicolon to finish your statement.

```css
picturesize {
  width: 25px;
  height: 25px;
}
```
This adjusts the pixel size of the animal image

### Size image
Go back to your index.html file and add ```className="picturesize"``` before the 'src'. This connects the CSS property to the image you want to resize!

```
<img className="picturesize" src="https://www.google.com/imgres?q=giraffe%20animal&imgurl=https%3A%2F%2Flionhabitatranch.org%2Fwp-content%2Fuploads%2F2023%2F09%2FMeet-Ozzie-2.jpg&imgrefurl=https%3A%2F%2Flionhabitatranch.org%2Fanimals%2Fmeet-ozzie-the-giraffe%2F&docid=zEYiYylsmA5eRM&tbnid=5mxxKuPd_n-L5M&vet=12ahUKEwjQurKTpueJAxXiMzQIHbsCAF0QM3oECFkQAA..i&w=900&h=1200&hcb=2&ved=2ahUKEwjQurKTpueJAxXiMzQIHbsCAF0QM3oECFkQAA"/>
```



## Stretch Goals
If you finish early, feel free to add images of your favorite food to your website and resize them to all be the same size!
Hint: use the same CSS property:)
Make sure to size it the same as your other picture using CSS

## Conclusion

Congratulations! You've created a simple website using HTML and a little bit of CSS. This is just the beginning – there are many more features and technologies to explore. Keep learning and experimenting to build more complex and dynamic websites.

Feel free to reach out if you have any questions or feedback. Happy coding!
