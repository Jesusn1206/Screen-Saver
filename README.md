This was an assignment for my Computer Graphics (COP 4710) class in Florida International University
Spring 2024

The assignment was as follows:

For this programming assignment, you need to complete the “Screen Saver” program posted
on Canvas. This program is based on the one you implemented for the second programming
assignment (the polygon Shader). This program creates an animation in which polygons
move around, rotate, and bounce when hitting the borders of the display window. User
can make the polygons on the screen start/stop moving by pressing the space bar on the
keyboard. The Screen Saver program must provide a graphical UI for the user to:

Figure 1: Menu items in the main form of the application for opening a display window and
manipulating the draw/fill settings.
 Input convex polygons by moving mouse over the display window (like PA2)
 Specify the fill color(s) and fill pattern of the drawn polygons (like PA2)
 Specify the border color(s) and border pattern of the drawn polygons (like PA2)
 Specify the initial rotation direction of a polygon (clockwise or counter-clockwise)
 Specify how fast a polygon must rotate
 Specify the initial movement direction (right-up, left-up, right-down, left-down)
 Specify a polygon’s constant movement speed (represented by two non-negative numbers vx and vy). Please note that the polygon keeps the same movement speed for its
whole lifetime.
 Specify the whether or not a polygon shrinks when hitting the display window border
and bounce.
 Specify the shrink ratio of a polygon in the case that it shrinks when bouncing.
 Specify how fast a polygon shrinks when bouncing.
 Input a circle and add it to the display window by entering the numerical values of its
radius and the x-y coordinates of its center.
Figures 1 and 2 show the menus available in the main form of the program allowing the user
to open a window, change the color settings, change the movement settings, and add a circle
to the display window of program. Keep in mind that any change in the settings will affect
only the polygons drawn after the change.
The user expects to see that an appropriate dialog opens up whenever one of the menu
items is clicked. The user should be able to input relevant information through a dialog by
typing some text and then clicking on the OK button of the dialog to confirm the input (just
like the way PA2 was designed).

Menu items in the main form of the application for manipulating the movement
settings and adding a circle.

