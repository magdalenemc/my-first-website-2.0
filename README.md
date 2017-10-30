# First Website 2.0
Using jQuery to add interactivity to your first-website project.

---

**Table of Contents**
- [First Website 2.0](#first-website-2.0)
  - [Setup](#setup)
    - [Revisiting your First Website](#revisiting-your-first-website)
  - [Lesson Steps](#lesson-steps)
    - [TODO 1 : Create Another Container div](#todo-1--create-another-container-div)
    - [TODO 2 : Create a Professional Content div](#todo-2--create-a-professional-content-div)
    - [TODO 3 : Add HTML Elements](#todo-3--add-html-elements)
    - [TODO 4 : Style Your New Section with CSS](#todo-4--style-your-new-section-with-css)
    - [TODO 5 : Import jQuery](#todo-5--import-jQuery)
    - [TODO 6 : Create a jQuery Function for Your Button](#todo-6--create-a-jQuery-Function-for-your-button)
    - [TODO 7 : Commit and Push Your Changes to Github](#todo-14--go-live)

---
## Setup
### Revisiting your First Website

The goal of this project is to spruce up our first website by creating a new `<div>` (from scratch!) and adding some jQuery to that section. Let's get started, shall we?

1.  Open up your first-website workspace on cloud9 (http://c9.io)
2.  Open up the `index.html` file for first website. Make sure you've chosen index.html for the website, not any of your other projects. You can assure this by closing the projects folder. The correct `index.html` file will be at the bottom of the file list.

That's it! You're ready to make your website swanky.

---
## Lesson Steps

### TODO 1: Create Another Container div
First, find the div with the class 'container' in the HTML of your `index.html` file. It should look something like this:
```HTML
  <div class="container">
     <div class="sidebar">
        <img src="http://ventureforamerica.org/wp-content/uploads/Magdalene-McArthur-e1470163838324-500x500.jpg">
     </div>
           
     <div class="personal-content">
       <header>Magdalene McArthur</header>
         <p>Instructor at Operation Spark</p>
           <section class="interests">
             <header>Interests</header>
               <ul>
                 <li>Traveling</li>
                 <li>Reading</li>
                 <li>Cooking</li>
                 <li>Cooking</li>
               </ul>
           </section>
      </div>
    </div>
```
Once you've found it, we're going to create a *new* container div right beneath it. Right below the closing `</div>` tag, create a new `<div>` with the class `container2` like so:

```HTML
<div class="container2">
  
</div>
```

### TODO 2: Create a Professional Content div
Awesome! Now that you've created your container div, we're going to create another div that will hold the information for your professional interests. 

Inside the `container2` div, create another `<div>` with the class `professional-content` like so:
```HTML
<div class="container2">
  <div class="professional-content">
  
  </div>
</div>
```
### TODO 3: Add HTML Elements
Now, the fun begins. We've structured out our divs, so now it's time to add some content. Add the following to your `professional-content` div:

1.
2.
3.
4.
### TODO 4: Style Your NEw Section with CSS
### TODO 5: Import jQuery
### TODO 6: Create a jQuery Function for Your Button
### TODO 7: Commit and Push Your Changes to Github
