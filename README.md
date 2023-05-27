# Complete Development Environment 2023

## HTML classname conventions

#### The conventions described below are just something I (Edwin Björlin) use. I got tired of always coming up with new systems for each project so that is why I've documented my thought process below. If you find this logical I suggest you use it aswell, otherwise try to come up with a system that suits you. Happy coding!
```HTML
<div class="section--projects">
    <h1>Projects</h1>
    
    <div class="container--projects">
        <div class="component--project-card">
            <img src="/media/images/projects/1.jpg" alt=""/>
            
            <div class="part--project-info">
                <h1>Project 1</h1>
            </div>
        </div>
        
        <div class="component--project-card">
            <img src="/media/images/projects/1.jpg" alt=""/>
            
            <div class="part--project-info">
                <h1>Project 2</h1>
            </div>
        </div>
    </div>
</div>
```

### section--*
Holds:
- Containers
- Components
- Parts
- Elements

Examples:
- section--projects
- section--employees
- section--reviews

---

### container--*
Holds:
- Components
- Parts
- Elements

Examples:
- container--projects
- container--employees
- container--reviews


### component--*
Holds:
- Parts
- Elements

Examples:
- component--project
- component--employee
- component--review


### part--*
Holds:
- Elements

Examples:
- part--name-and-technology
- part--name-and-position
- part--name-and-rating


### elements
Examples:
- h1, h2, h3, h4, h5, h6
- p, a, span
- img, video


### order of css attributes

## logical sizing
thin, thicker, thickest
small, medium, large
narrow, regular, wide

## alphabetical
Look at first letter, if samek, look at 2nd, third and so on
IF one word is identical in the beginning like padding and padding-left, then padding should be on top.
--color--background: #FFFFFF;
--color--faint: rgba(0, 0, 0, 0.3);
--color--text-primary: #000000;


### spacing between
2 or more that starts with same letter spacing around them
