# Chloe Wildman's Assignment 3 - Portfolio

To meet the assignment requirements, I built a single page portfolio containing a mixture of pre-existing and class-related projects.

To test this page, please try the following test cases:
- View the page on a desktop.
- View the page on a mobile device.
- Hover over clickable elements such as the project tiles and the LinkedIn, Github, and email icons.
- Tab through the elements (to activate :focus styling).
- Scroll the the bottom and select "Back to Top".
- Hover over/try to click the "coming soon!" project, which is unavailable.

## Inspiration/Acknowledgements/Previous Experience

### Module 3 Content

My general structure was inspired by the Wednesday lecture. In that lecture, the professor used the grid format consisting of the header, main (with sidebar and additional content) and the footer. This looked clean and manageable, so I implemented a similar format, with an additional grid to organize my projects separately.

### WAD100 Course

The use of reset.css and some CSS was inspired by the WAD100 course. Here are the key items I used as inspiration:
- The use of reset.css (not really able to make this one unique!)
- The strategy to decrease font-size to 0 and use background images to display the clickable icons.

### Previous experience

In my day job, I was tasked with customizing a Help Center for my team, so I have some existing exposure and comfort with CSS.

### Online resources
Did some research to make the formatted line in the footer: https://www.w3schools.com/tags/tag_hr.asp 

I used Canva to build my CW logo: https://www.canva.com/

I used the Corporate Elegance color palette: https://piktochart.com/tips/professional-color-palette 

## How My Project Meets Minimum Requirements

### Web Page Structure
- My single-page portfolio contains:
    - header
        - contains logo and title
    - footer
        - contains copyright details and navigation links (back to top)
    - main
        - contains at least 4 projects
    - sidebar
        - contains personal information and contact links
- The layout is responsive on both desktop and mobile.

### Using CSS Flexbox and Grid
- I used flexbox in the header and footer to center content.
- I used CSS grid on the the main section and to display projects in a multi-column layout based on screen size.

### Pseudo-classes and Pseudo-elements
- Applied the following pseudo-classes:
    - :hover
    - :active
    - :focus
- Applied the following pseudo-elements:
    - ::before
    - ::after

### Combinators and Advanced Selectors
- Applied the following combinators
    - Descendant (space)
        - example: .item a {}
    - child (>)
        - example: .project > a {}
    - sibling (+)
        - example: img + h2 {}
- Applied the attribute selector to control the appearancfe of unavailable/disabled elements. This is controlling the "coming soon!" project tile.
    - [class~="unavailable"]
    - I also combined this attribute selector with pseudo-classes for increased control

### Validity
- Valid: 
    - https://validator.w3.org/
    - http://jigsaw.w3.org/css-validator/ 


## How My Project Exceeds Minimum Requirements
There are not defined criteria in the assignment for what would exceed minimum requirements, but I spent even more time on this assignment this week than I have on the previous assignments (and I'm taking my time on these to try and make the most of them). I found this one particularly motivating since it felt like it had more utility for me. I tried to take the opportunity to combine the different tools we learned this week beyond just implementing them individually to meet requirements. I think this site has turned out visually appealing and professional on both desktop and mobile, so I hope it has exceeded requirements.