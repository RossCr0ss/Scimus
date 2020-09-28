# Scimus

Test task with Pure HTML, Flexboxes, SCSS modules.

## FOLDER STRUCTURE

```sh
 src/*
      └─ css/*
        └─ style.css*
      └─ img/*
        └─ images…*
      └─ scss/*
        └─ _main.scss*
        └─ _variables.scss*
        └─ style.scss*
      └─ index.html*
      └─ koala-config.json*	* ¬¬¬- required
```



## TASK
In this archive you can find an index.html file with provided page markup, images, some prepared .scss files, and a design/ folder with expected results.
Your task is to generate two different css files according to design.
-	All required css rules and scss mixins should be written in _main.scss and variables should be  defined in _variables.scss file
-	Do not change file scss/style.scss. They already import all necessary partials
-	Add form fields in index.html files in TODO section and style them
-	scss file should use a nesting syntax
-	All distances between blocks should be set by yourself (tips: you can use Pixel perfect browser addon, but it isn’t required)
-	Header section with background image should take 100% of height and width of the viewport
-	No requirements for browser support (should correctly work in last version of Google Chrome)
Please use koala-app for compiling. Find a koala-config.json config file where compilation path is already set.
EXPECTED RESULTS
The styles.css are generated from source files.
Page design should match desing.png. When page is switched to use styles.css


## EXAMPLE

```sh
_main.scss:
body {
    background: $contentBackground;
}
main {
      margin: 0 auto;
      width: 960px;
}
...
_variables.scss:
$contentBackground: #fff;
```

## FONTS AND COLORS
Fonts: 
1)	normal 300 15px/24px Roboto, Ubuntu, Cantarell, Helvetica ,sans-serif;
2)	normal 18px/26px "Palatino Linotype", "Book Antiqua", Palatino, serif;

Feel free to use any tool which will help you to pick the right color. Colors should be as close to design as possible. 

## RESTRICTIONS
-	Do not use any CSS framework for this homework.
-	Do not use any others scss compilers except koala.
## BEFORE SUBMIT
-	Make sure you’ve done all steps, described result match the designs;
-	*.scss files compiles without any errors;
-	Make sure your code is well-formatted, and validated via validator:
HTML: https://validator.w3.org/  
CSS: http://jigsaw.w3.org/css-validator/

## SUBMIT
-	The folder should be uploaded to github repository into master branch

## USEFUL LINKS
-	http://koala-app.com/
-	https://sass-lang.com/guide

## License
[MIT](https://choosealicense.com/licenses/mit/)