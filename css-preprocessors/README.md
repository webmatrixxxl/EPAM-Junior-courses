# CSS preprocessors live coding demo


This is the simple page we codded at the end of the presentation. It is refined and complited.
To run it you need to clone the project and execute this comands to run SASS compiler and browser-sync web server. You should be in project folder e.g. "/css-preprocessors"

 First terminal
```sh
    npm i -g sass
    sass src/scss/style.scss assets/css/style.css --watch
 ```
 Second terminal
 ```sh
    npm i -g browser-sync
    browser-sync start --server --watch --files "**.*"
 ```
   ... and Magic 

# Homework
    
Part 1: 
  - Look cearfuly at the project code - **selectors naming, nesting, reusage, @mixins, @content, if, variables**
  - Figure out how the things work and if you don't get something write your questions and we will discuse them

Part 2:
  - Checkout https://www.sitepoint.com/sass-theming-neverending-story/ (you can research others as well)
  - Choose theming method
  - Apply it to the project (page background, "main" and "second" sections color and button styles)
  - Upload your implementation in github and send me links


