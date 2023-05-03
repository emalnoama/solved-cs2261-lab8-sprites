Download Link: https://assignmentchef.com/product/solved-cs2261-lab8-sprites
<br>
In this lab, you will be completing several different TODOs, which will, piece by piece, complete an animated pikachu character that the player can control. Your code may not compile until you complete an entire TODO block, at which point the game should compile with a new component of the final outcome (unless otherwise specified).




<strong>TODO 1 – Exporting the tiles </strong>

We need to export the backgrounds and tiles in order to use them in the code.

<ul>

 <li>0: Open bg.bmp in Usenti.</li>

 <li>TODO 1.1: Go to Image &gt; Export, keep the default name, and make sure the type is GBA Source. Make sure it is exporting them to your Lab08 folder.</li>

 <li>TODO 1.2: In the Export popup, make sure the type is 4bpp tiles, and make sure that Pal is checked and Map is checked, because this is a background.</li>

 <li>3: Open sprite sheet.bmp in Usenti.</li>

 <li>TODO 1.4: Go to Image &gt; Export, keep the default name, and make sure the type is GBA Source. Make sure it is exporting them to your Lab08 folder.</li>

 <li>TODO 1.5: In the Export popup, make sure the type is 4bpp tiles, and make sure that Pal is checked and Map is ​<strong>not </strong>​checked, because this is a spritesheet.</li>

 <li>TODO 1.6: Add the new .c files to your Makefile.</li>

</ul>

At this point, we haven’t added them to your code, so compiling will not do anything useful.




<strong>TODO 2 – Displaying the Background </strong>

We want to be able to actually see the background, so let’s set that up.

From now on, the TODO’s will have their description in the code. Their location in the file will be listed here.

<ul>

 <li>0: Top of main.c.</li>

 <li>1: main.c, initialize() function.</li>

 <li>2: main.c, initialize() function, under REG_DISPCTL. Compile and run. You should see the background on the screen. If not, then you either exported wrong or did not load the tiles or map into memory correctly. Fix this before continuing.</li>

</ul>




​<strong>TODO 3 – Loading and Enabling Sprites </strong> Let’s get sprites working.

<ul>

 <li>0: main.c, initialize() function.</li>

 <li>1: myLib.c, hideSprites() function.</li>

 <li>2: main.c, initialize() function</li>

</ul>

Compile and run. You should not see anything new. If you see anything in the top-left (CORNERFACE), fix this before going further.




​<strong>TODO 4 – Animating Sprites </strong>

Let’s show pikachu, and get animations working.

<ul>

 <li>0: main.c, bottom of initialize() function.</li>

 <li>1-4.9: main.c, in the main while loop.</li>

</ul>

Compile and run. You should be able to walk pikachu around infinitely, see your background repeat, and all the while pikachu stays in the middle of the screen. If this all works, submit your lab.


