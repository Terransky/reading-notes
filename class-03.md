From the Duckett HTML book:

Chapter 3: “Lists” (pp.62-73)
Chapter 13: “Boxes” (pp.300-329)
From the Duckett JS book:

Review from Reading 02 - Chapter 2: “Basic JavaScript Instructions” (pp.70-73)
Chapter 4: “Decisions and Loops” from switch statements on (pp.162-182)

* HTML Chapter 3: Lists
  * Lists in html are denoted with ol (ordered) and ul (unordered) with individual li elements for each item.
  * Definition lists use dl tags and a dt tag for the term and dd for the description of that term.
  * Lists can be nested.

* HTML Chapter 13: Boxes
  * HTML elements can interpretted as being enclosed by boxes with margin, border, and padding. We can resize these boxes.
  * Width and height can be set as well as limit imposed width or height with a max or min value.
  * Overflow allows for smaller boxes and text that exceeds the space can be scrolled through.
  * Border lines can be stylized and given varying thickness. Each side can be independently given size and color variation.
  * Padding puts white space between the content and the border.
  * Margin determines the space between boxes (elements).
  * To center content, set margin to auto.
  * Elements can be changed to inline or block level with the display property. Setting it to none deletes it and takes it out of flow.
  * The visibility property can be set to hidden or invisible. It will still retain the space and margin of the element on the page.
  * border-image gives a border an image. box-shadow gives an element a shadow and 3D effect.
  * Borders can be given rounded corners or eliptical shapes.

* JS Chapter 2: Basic Javascript Instructions
  * Arrays are a special type of variable that can store a list of values.
  * It is denoted with square brackets.
  * Values within an array are indexed starting at 0. The individual indices can be accessed and assigned different values.

* JS Chapter 4: Decisions and Loops
  * Switch statements are very similar to if and if else statements that would only activate from a single condition like an integer.
  * Javascript can use type coercion and weak typing to try and make sense of unexpected type input for conditionals but we turn this function off with "use scrict".
  * We can still use truthy and falsy type coercion though. Non 0 integers evaluate to true and 0 to false, for example.
  * Any string that isn't a space also qualifies as truthy. This can be used with if statements that simply check for the existence of an object.
  * Because logical operators are processed from left to right and immediately short circuit as soon as they evaluate as true, the OR operator can be used within assignments to variables to pick from a left or right value.
  * Loops check a condition and will run indefinitely so long as that condition is true.
  * Loops can be broken out of with break or stopped short but continue on to the next iteration with continue.
  * The difference between a while and do while is that the do while always runs the initial statement (the do) at least once.