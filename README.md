# 20-10-29 HTML CSS Overview Primary

### Set Up
1. copy the assignment git url in github after accepting the assignment
1. clone the assignment in the `html-css-basics` directory using `git clone COPIED URL`
1. open the assignment in VSCode

### Linking files
1. create an html file called `index.html` and `details.html` and use the `html:5` shortcut to generate the html, head, and body elements in both
2. create a css file called `style.css`
3. link the css file to each html file using the `link` tag in the `head` of both HTML files - set the `rel` attribute to `stylesheet` and the `href` attribute to the css file path
```html
 <link rel="stylesheet" href="style.css">
```
4. check that the files are linked by setting the `background-color` property of the body to any color other than white/gray and open both HTML files using `ctrl o` in the browser

### Assignment
Recreate the wireframe images provided. The index page should look like `wireframe1` and the details page should look like `wireframe2`.

### Content

#### Index
1. Create a heading one element with the text `Landing`
1. Create a button that links to the `details.html` file with the text `Learn More`
1. Create a container element with a paragraph element with filler text
1. Embed a YouTube video about web development using the `iFrame` 
1. Create a container element with a paragraph element with filler text 

#### Details
1. Create a heading one element with the text `Details` 
1. Create a button that links to the `index.html` file with the text `Back to Home`
1. Create a button that links to the site that you downloaded the image below the buttons with the text `Page Source` that opens in a new tab
1. Download an image related to web development to your assignment directory and display the image by file path using the `img` tag
1. Create a container element with a paragraph element with filler text
1. Create another container element with a paragraph element with filler text

### Styling
1. Style the text of all font to a sans-serif font
1. Add space between the content of the body and the window using padding or margin
1. Make all buttons green with a thin black rounded border and white text
1. Use a `class` to style the matching container elements on the index and details page to a green background, white text, and a black border on the left 
1. Give the iFrame on the index page and the image on the details page a thick green border
1. Center the iFrame on the index page and the image on the details page by setting the width and adding margin to each side

### Push File Changes in the Terminal
1. `git status` : check if file changes have been made
1. `git add -A` : stage changes for commit
1. `git commit -m "meaningful message"` : commit changes with appropriate message
1. `git push` : reflect local changes remotely 

### Resources
[Concept Documentation Info on HTML + CSS](https://github.com/cs-parttime-2020-fall/part-time-program-syllabus/blob/master/html.md)

[Google Fonts](https://fonts.google.com/)
