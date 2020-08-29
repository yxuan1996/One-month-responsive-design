# One-month-responsive-design

## Key Concepts in Responsive Design
#### Flexible Grid
Columns can expand or contract based on size. 

#### Flexible Images and Media
Images adjust and extend so that they're 100% visible no matter what the size of the view is. 

#### Media Queries
Breakpoints can be set for different device sizes. 

## Basics
**Pixels** - The smallest discrete, controllable point on a display screen. Each pixel helps to make up what you see on your monitor. 

**Rems** - Flexible units of measurement. 

Let's say you have a div with a stated font-size of 10px and let's say that inside that div you have a paragraph. If you set that paragraph's font-size to 2rem, it multiplies by the parent font-size of 10px, giving the paragraph an equivalent size of 20px. Set the paragraph font-size to 1.6em and the equivalent size of 16px, and so on.

The **rem** unit of measurement stands for "root em." While an em is a multiple of the font-size of the parent, a rem is a multiple of the root element, which is the html element that wraps all of our html.

**Section and Aside** - HTML5 introduces some new components to make our code easier to read. Section and Aside are basically div components. The names reflect their purpose, nothing more. At the end of the day they are just divs. 

## Techniques
#### Media Queries
For this tutorial, we create 2 separate stylesheets. 
`styles.css` is the default stylesheet
`small.css` defines styles for smaller screens

`small.css` will only load for screens smaller than 630 px
```
<link rel="stylesheet" href="css/small.css" media="(max-width: 630px">
```

To ensure that images fit the size of the screen, we wrap out images in a div class `.container`. 
In the default stylesheet, we set the maximum width of the div class to 600px
In the small stylesheet, we set the width of the div class to 100%

## Skip
The videos were long and rambly, skip. I have uploaded the final completed answers. 
Note to self: Stick to bootstrap for now. 

