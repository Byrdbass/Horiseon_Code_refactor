# Refactoring Homework unit 01-HTML-Git-CSS

I was called upon to the existing code into more semantic HTML code.  The existing code did not contain accessibility standards.  Below is a list of improvements made to both index.html and style.css.
---
## index.html refactoring and updates
- changed the title of the webpage to **Horiseon Marketing**
- added the Nav element to the header
- added the figure element for the large photo (jumbotron) on the top of the screen
- replaced the div elements to main and 
- replaced the div elements to aside for Semantics
- the "Search engine optimization" section of the main element was missing the link from the nav bar" - added `id=#search-engine-optimization`
- changed the div elements to section elements for more clarification on semantics within main and aside
    -one example is below
![picture of original HTML with non-Semantic HTML ciricled in red](assets\images\originalHTML_HoriseonHW.png)


## CSS properties
-consolidated some of the repeated properties in the style that were the same in multiple classes -an example is shown below

![picture of original CSS with redundancies across mulitple classes circled in red](assets\images\originalCSS_HoriseonHW.png)

# What i learned
I found this exercise to be challenging in my workflow for editing existing code.  I realized that I should not be deleting things in both the style.css as well as the index.html, but I should simple comment each edit i was making to make sure i did not loose the original source code.  I also found that making commits more frequently in GitHub would of made this process more apparent to my future self or anyone that wished to view my work.  Luckily, I still had the original HTML and CSS files in a seperate folder, and changed the location of my repository on my local machine.  Lastly, I found i understood the syntax in CSS when applied to multiple classes.  I was listing some of the CSS properties without the iteration of the comma.  At first i failed to understand the headers or images within each class could belong to their parent and function seperatley in style from the parent class.

You may find the deployed webpage [here](https://byrdbass.github.io/Horiseon_Code_refactor/)

Thank you for reading and viewing!
