From the Duckett HTML book:

Chapter 4: Ch.4 “Links” (pp.74-93)
Chapter 15: “Layout” (pp.358-404)
Note: This layout chapter is BIG. Focus your attention on understanding the core concepts presented on pp.358-364, and look at the code samples on the website that accompanies the textbook. You will have another reading assignment on this chapter, so do not try to digest it all now.

From the Duckett JS book:

Chapter 3 (first part): “Functions, Methods, and Objects” (pp.86-99 ONLY)
Article: “6 Reasons for Pair Programming”


* HTML Chapter 4: Links
  * Links are made using the a element with a hyperlink reference, or href attribute with a value of the link.
  * Relative URLs can link to local pages in the same directory or parent/child directories.
  * The root level folder is the top.
  * The target attribute will open links in a new window.
  * Elements with IDs on the same page can be href'd with a # to jump to that part of the page.

* HTML Chapter 15: Layout
  * Each HTML element is treated as a box. Block level elements start on new lines and inline elements do not.
  * Normal flow is denoted with position: static.
  * position: relative will move the element however many pixels specified from where it would have appeared in normal flow.
  * position: absolute sets the element at the specified coordinates of its container and will overlap with other elements.
  * position: fixed sets the element in relation to the browser window, allowing things like headers that are always at the top as a user scrolls.
  * z-index: number will give an element a z value that determines its priority when overlapping.
  * float: right/left will take an element out of flow and send it all the way to the left or right and force other elements to flow around it.
  * floating elements is a common technique to place them side by side.
  * the clear property can address some height issues that arise with float by not allowing the sides of that element to be touched.
  * Elements normally stack on top of the other but columns can be made by giving an element a width and floating them next to each other.

* JS Chapter 3: Functions, Methods, and Objects
  * A function can group a series of statements to perform a specific task and be invoked later.
  * It can have parameters which accept arguments and return values to used wherever needed.
  * A function is declared specifically as such and followed by a name and block of code. It can be invoked by that name() later.
  * It can be declared with parameters that accept arguments to be passed into the interior code.
  * A function can return a single value or multiple using an array.
  * Function declarations can be written below its invocation because the interpreter processes all the variables and functions before running the code.
  * However, a function expression assigned to a variable will not and must be used in sequence.
  * Nameless, disposal functions can be written to immediately activate when the interpreter comes across it and won't be saved and can't be invoked later.
  * Variables declared within functions are locally scoped and only exist in that code block.

* Article: 6 Reasons for Pair Programming
  * It can lead to greater efficiency since two brains and pairs of eyes can more easily catch mistakes as they're made. Brainstorming the code together can also lead to whole greater than its sum. Two heads are better than one.
  * Engaged collaboration uses peer pressure to keep both members on task and acts as a lifeline when stuck on a problem.
  * Pairs can learn from each other, especially if they have different ways of approaching the same problem.
  * It improves social skills and the ability to speak coherently about code.
  * It can help with job interviews since many of them include a segment where you collaborate on a coding challenge with the interviewers and it showcases how well you might work on their team.
  * Many companies utilize pair programming on fresh graduates to get them up to speed anyway, so Code Fellow grads are one step ahead of the game.