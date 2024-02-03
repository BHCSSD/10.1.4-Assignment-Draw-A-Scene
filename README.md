# 10.1.4-Assignment
Graded
# P5 Assign 1 Draw a Scene

## Marking
- 80% - drawing the scene with the requirements below
- 10% - proper indenting is maintained (Tidy your Code and fix your indenting)
- 10% - proper commenting is included, end of function comments: "} // end draw", what each part of your code does aka //snowman head, //bat body etc

## Set Up
1. Create a canvas that is 700 x 700 with a background of your choice
2. Then in draw(), add 3 lines of text at the top of the window:   



## Main Task
Your goal is to draw one of the following things/scenes.  
1. a house on a street
2. an old school iPod
3. a car or truck or submarine
4. a snowman
5. a Minecraft Creeper
6. Stanley Cup or other trophy
7. For a tougher challenge, try a colorful Canadian Flag
8. Any other scene that you can think of

## Your drawing must include:
- A background colour
- At least 10 shapes, including all of the following:
  - Lines
  - Rectangles -or- squared
  - Ellipses -or- circles
  - Optional shapes: triangles, quad, arc
 - some shapes must be filled, using multiple colours
 - You could also use random(255) to affect your color codes.
 - multiple stroke thicknesses of lines. Example:  strokeWeight(5);
 - 3 lines of text somewhere on your drawing

## Tips
- It is sometimes easier to draw with:  `rectMode(CENTER);`
- Then if you want to go back to normal rectangle mode:	`rectMode(CORNER);`
- Consider using noFill()  & noStroke()

## Done early?  
- Practice adding a Font and give your artwork a title.
- Try animating your picture.  Can you make your snowman wave by moving your mouse? Or add a bird that flies across your screen.
- If you already know how to add images, or figure out how to include a picture as a background.  For example, you could have a winter scene picture behind your snowman.  To do this you do NOT use the background( ) code, you just put the right sized image at 0,0.  Example: image(snowscenePic, 0, 0, 400, 600);

