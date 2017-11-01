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
First, find the `main` tag in the HTML of your `index.html` file. It should look something like this:
```HTML
  <main>
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
    <main>
```
Once you've found it, we're going to create a *new* container div right beneath it. Right below the closing `</div>` tag, create a new `<div>` with the class `container` like so:

```HTML
<div class="container">
  
</div>
```

### TODO 2: Create a Professional Content div
Awesome! Now that you've created your container div, we're going to create another div that will hold the information for your professional interests. 

Inside the `container` div, create another `<div>` with the class `professional-content` like so:
```HTML
<div class="container">
  <div class="professional-content">
  
  </div>
</div>
```
### TODO 3: Add HTML Elements
Now, the fun begins. We've structured out our divs, so now it's time to add some content. Add the following to your `professional-content` div:

1. Create a `<header>` tag that will read `Professional Interests`
2. Create a `<section>` tag with the class `intrests`
3. Create a `<button>` tag. The button should say `use me to see my professional intrests`
4. Create an `unordered list` of three professional interests you have. They can be programming languages you're interested in learning, fields of study you're considering for college, or careers you're interested in.

Your end result should look something like this (don't copy this code, just use as a reference):
```HTML
  <div class="container">
    <div class="professional-content">
      <header>Professional Interests</header>
        <section class="interests">
          <button>Use me to see my professional intrests</button>
            <ul class="professional-interests">
              <li>JavaScript Web Development</li>
              <li>Data Science</li>
              <li>Analyzing data using Python</li>
            </ul>
        </section>
     </div>
  </div>
```

### TODO 4: Style Your New Section with CSS
Now that your elements are created, it's time to add some styling to them in CSS. The container div that you just created should have all of the exact same styling rules as the first container div.

1. Find the CSS selector for the original container `<div>` and all the elements within it.
2. Create a new selector for the `container` `<div>` and all of the elements within it.
3. Mimic the style rules from the first container so that the new section we created looks just like it!

### TODO 5: Import jQuery
Now that we've created our HTML elements, it's time to start adding some jQuery to our page.
First, import the jQuery library by pasting the following code into your `<head>` tag, underneath the closing `</style>` tag:
 ```HTML
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
```
### TODO 6: Create a jQuery Function for Your Button
Now let's add some interactivity to the button we created in our HTML Code.
1. First, create another `<script>` tag, underneath the jQuery library source, like so:
```HTML
<script>
  
</script>
```
2. Now, within the script tag, we're going to create a function that adds some type of motion to your unordered list of interests, using the button we created. 

An example of this would be your list appearing and dissapearing every time someone clicks the button.

Start by creating a function like so:
```HTML
<script>
 $(document).ready(function(){
                
  });
</script>  
```

3. Next we need to add a JQuery event that will trigger every time the button is used. This action will be up to you! Some examples are listed here for you:
(https://www.w3schools.com/jquery/jquery_events.asp)

4. Finally, inside that event, add some action to your unordered list. This will also be up to you. Use google and the link below to find more jQuery effects. 
(https://www.w3schools.com/jquery/jquery_ref_effects.asp)
Make sure to google how to effectively access the unordered list in order to use it in the jQuery effect. An example will be provided below.

In this example, once the button is clicked, the list of interests will appear or disappear (don't copy, just use as a reference):

  ```HTML
        <script>
            $(document).ready(function(){
                $("button").click(function(){
                    $("ul.professional-interests").toggle();
                });
            });
        </script>
  ```
  Now you've done it! You've created an awesome, upgraded first-website!
### TODO 7: Commit and Push Your Changes to Github
Enter the following commands, and be careful to place your spaces correctly and press `ENTER` after each one. Read the results of each command and check for errors.

First, add all the files we worked into git so that they can be archived in our source control:

1. First, **add** all the files we worked into git so that they can be archived into a set of changes in our source control:
    
        git add -A

2. Then **commit** everything that has been added to the set of changes:
    
        git commit -m 'A basic website'

3. Finally, sync the repository in cloud9 with the one on github by **pushing** your set of changes. **If** you are prompted, just type 'yes' to proceed, but you may not be asked.
    
        git push
    
If asked, enter your Github username and password. 
