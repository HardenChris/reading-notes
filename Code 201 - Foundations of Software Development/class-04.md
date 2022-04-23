# HTML links, layouts w/ CSS, Funcs. in JS

## Ch. 4 - Links / HTML & CSS

* **Links** -Are a major part of any website. Links are the portals from page to page, or from one site to another, or from one part of a page to another. Example:

  * ```<a href="https://www.facebook.com">Facebook</a>```

* **Directory Structure** - how you organize your directory. This is important because a clear directory structure leads to a better clearer understanding of paths.

* **root** - refers to the highest folder. the father of all fathers.

* **Homepage** - is usually **index.html** this is the default and the base page most pages go to.

* **Relative URLs** -  used when going to a page inside of your own website. Relative URLs is a shorthand that shows you where the destination is at in relation to your current location.

  * Same folder - just use the name nothing else is needed.

  * Child folder - for a child use the child folder name followed by a forward slash then file name.

  * Grandchild folder - child name, forward slash, this name of grandchild folder, followed by a second forward slash.

  * Parent folder - use ```../``` to indicate the folder above this one. Then file name.

  * Grandparent folder - ```../``` followed by another ```../``` then file name.

* **Target** - opens a link in a new window. ```_blank``` should be assigned to Target. Example:

  * ```<a href="https://www.facebook.com" target="_blank">```

## Ch. 15 - Layout / HTML & CSS

* **Building Blocks** - Css treats each HTML element as if it is in its own box.
  * Block-Level Elements - starts on a new line
  * Inline Elements - Flow in between surrounding text

* **Containing Elements** - if one block-level element sits inside another block-level element then the outer box is knowm as a parent or containing element.

* **Positioning Schemes** - this allows you to control the layout of a page.

  * Normal Flow - Every block-level element appears on a new line, causing each item to appear lower down the previous one.

  * Relative Positioning -  moves an element from the position it would be in normal flow, shifting it to the top, right, bottom, or left of where it would have been placed.

  * Absolute Positioning - positions the elements in relation to their containing element. It is taken out of the normal flow and does not affect surrounding elements.

  * Fixed Position - a form of absolute positioning positions the element in relation to the browser window, as opposed to the containing element.

  * Floating Elements - an element allows you to take the element out of the normal flow and position it to the far left or right of a containing box.

  * Z-index - is a property that controls which box appears on top.

* **Page Sizes**  - web pages are usually designed after the standard 960-1000 pixels wide.

  * Fixed Width Layouts - does not change size as the user decreases or increases the size of the browser window. Usually are based on Pixels.

  * Liquid layouts - will stretch and contract as the user decreases or increases the size of their browser window. Usually use percentages.

## Ch. 3 Functions, Methods, & Objects / JS & JQUERY

**Function** -lets you group a series of statements together to perform a specific task.

    - Declaring a func - to creat a func, you give it a name and write statements to achieve a task.Also functions are written in camelCase. Example:
        * function sayHello() {
            document.write('Hello!');
        }

    - Calling a func. - after declaring a function you can execute all of the statements between its code brackets. Example: 
        * sayHello();

    - Declaring func. that needs parameters- Below is an example and when you want to fill it in you have to pass parameters to it namely a height and a width:
        * function getArea(width, height) {
            return width * height
        }

        getArea(5,3) -> return 15

    - you can get a single value out of a function or multiple values out of a function and into a array.

## 6 Reasons for Pair Programming

* **Pair Programming** - is the process of two devs share one workstation and code together. Pair programming tends to give many benefits including linting, fast feedback, code review, and more. The two roles are Driver and Navigator. Navigator teaches and guides while the Driver does all of the typing.

* The six points listed in the article are:

    1. Greater efficiency - coding together means fewer issues and fixes need to come later.

    2. Engaged Collaboration - When there is two coders working on one code they tend to make better choices and be more focused.

    3. Learning from a fellow student - two minds are not alike so you both will think differently.

    4. Social Skills - when you code you have to talk. simple as that.

    5. Job interview ready - many jobs do pair programming as a part of the hiring process.

    6. Work environment ready - many companies teach new hires using pair programming.

Duckett, J (2011). HTML & CSS design and build websites, 74-93,358-404

Duckett, J (2011). JAVASCRIPT & JQUERY Interactive front-end web development ,86-99

Grampa, Allie. "6 Reasons for Pair Programming"CodeFellows,CodeFellows, 24 August 2018,<https://www.codefellows.org/blog/6-reasons-for-pair-programming/>

All definitions and information came from above listed publication.

[<===Back>](README.md)
