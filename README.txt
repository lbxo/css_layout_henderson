A Pen created at CodePen.io. You can find this one at https://codepen.io/lbxo/pen/OzeKOR.

 # CSS Layout Basics Challenge
Here we have two sections of Louie's Pizza site.  Currently the text in these two sections span the entire width of the page, with no padding whatsoever. This makes the text difficult to read, especially on larger screens.  Let's apply a little bit of layout using some basic css and a media query.  

## Mobile First Layout
1. Create a css class named `wrap`.
2. Add a padding of `2rem` to the `wrap` class, and make the wrap class center horizontally by giving it an automatic margin on the left and right side.  Leave the margin at 0 for the top and bottom.  

## Desktop Layout
Now that we fixed up the layout a bit on mobile, it's time to address the desktop view.  The text is still difficult to read on larger screens, since it spans most of the screen.  Let's use a media query to fix the desktop view. 

1. Add a media query that applies to screens that are 969px or larger.
2. In the media query, set the width of the wrap class to be 970px.

You can play with these two values to find breakpoints that may work better depending on the screens you are targeting.  A breakpoint at 769px is also common.  