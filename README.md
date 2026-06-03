# AutoCAD Learning
This repository documents my personal learning journey using various AutoCAD LinkedIn Learning courses using the AutoCAD 2027 15 day trial.

**Disclaimer**: I do not own the copyright to the course videos or original exercise files. All rights belong to LinkedIn Learning and Shaun Bryant. 
**Repository Content**: The files in this repository are **my own practice drawings and notes** created while following the courses. They are shared here to demonstrate my progress and understanding of AutoCAD.

## Learning AutoCAD 2026
The content below represents my personal notes and summaries derived from the LinkedIn Learning course "Learning AutoCAd 2026" by Shaun Bryant. All original course materials (videos, exercise files) are copyright of LinkedIn Learning and are not included in this repository. The course is linked below, note that it requires authorization to access via membership.

[Learning AutoCAD 2026 course by Shaun Bryant](https://www.linkedin.com/learning/learning-autocad-2026)

### Course Learning Outcomes
<details>
<summary> 1. Introduction </summary>
  
  Key Takeaways:
  * Introductory course to basic knowledge in AutoCAD in preparation for the Essential Training course.
  * Exercise files are provided in DWG 2013 format.
  * Explored the AutoCAD Interface (toolbar, ribbons, status bar) using a .dwg file of an office building.
  * Completed Introduction quiz, 2/2.

  <details>
  <summary> Introduction.dwg - AutoCAD Interface Layout </summary>

  > Introduction.dwg is a floor plan of an office used to explore the AutoCAD Interface.
  * "Model" Tab - where all design work is done in AutoCAD.
  * Quick access toolbar and ribbon, similar to Word or SolidWorks layout.
  * Status Bar controls drafting settings within AutoCAD, used to draft a model accurately and precisely.

  </details>
</details>

<details>
<summary> 2. The AutoCAD Interface </summary>
  
  Key Takeaways:
  * How to use the application menu and the quick access toolbar.
  * Interacting with the ribbon and ribbon panels.
  * How to use dialog boxes and palettes.
  * How to use the status bar.
  * Using web and mobile with AutoCAD desktop.
  * Challenge - dock the layer properties and set auto-hide property.
  * Completed AutoCAD Interface Quiz, 5/5.

  <details>
  <summary> Interface.dwg - AutoCAD Interface Layout </summary>

  > Interface.dwg is a floor plan of another office building, used to dive deeper into the AutoCAD interface.
  
  **Application Menu**
  * The application menu can be used to open a file, create a new file, save the current file in multiple formats, convert dwg format, import/export, publish, etc.
  * Files can be sorted by ordered lists and can be viewed as icons or images.
  * The options box can be used to modify settings of AutoCAD functionality, like display, save/open settings, system, drafting, etc.
  * Quick access toolbar parks often used settings at the top of the program like open, save, undo and redo. It can also be customized (ex. layers).

  **Ribbons and Panels**
  * Opens to the home tab by default.
  * The ribbons are divided into panels, like Draw, Insert, View, etc. Very similar to MS Word or SolidWorks division.
  * Each Panel has a specific use case, i.e. Annotate - Text, Markup, Dimensions, etc.
  * Pins can be used to expand the panel until it is unpinned.
  * The white button at the top of the ribbon is used to alter the display of the ribbon at the top of the program.

  **Dialog Boxes and Palettes**
  * Dialogue boxes have a title at the top and often contain tick boxes or settings that can be toggled.
  * Resizing dialogue boxes return to a default size when making them smaller.
  * Palettes have the title vertically on the side and contain various tools within them.
  * Resizing a palette also have a default minimum size, but you can minimize them to just show the title bar.
  * You can also expand or reduce the columns in palettes, change the transparency, or dock them.

  **Status Bar**
  * Allows you to work quickly with certain processes in AutoCAD.
  * AutoCAD runs using dynmode - i.e. if you start typing "line", a menu box will appear next to the crosshair.
  * Dynamic input can be displayed in the status bar menu, but is off by default. Blue = on, grayed = off.

  **Web and Mobile**
  * Part of the AutoCAd subscription is the web and mobile variants.
  * Web allows you to use a browser based interface, and similarly mobile allows you to use AutoCAD on a tablet or phone.
  * You can also save files to the web and mobile folders via cloud storage on the quick access toolbar.

  **Challenge**
  
  Dock the Layer Properties manager Palette on the left side of the screen and configure auto-hide so it expands when hovered over and disappears when left.
  * To achieve this, I opened the Layers Property Manager, then dragged it to the left hand side so [it was docked.](https://github.com/ashthemech/AutoCAD-Learning/blob/0e62a0c408cc6ba15fcbe49a1262972c15a21546/AutoCAD%20Interface/Docked%20PM.JPG)
  * Then, I clicked the [auto-hide button](https://github.com/ashthemech/AutoCAD-Learning/blob/d2627833c4dce2a5a0cde41b6d136c15bce10713/AutoCAD%20Interface/Auto-hide%20PM.JPG) and now the LPM palette reveals itself when I hover over it, and hides when I move my cursor off the menu.

</details>
</details>

<details>
<summary> 3. Drawing Simple Geometry </summary>
  
  Key Takeaways:
  * How to use the zoom and pan for navigation in AutoCAD drawings.
  * Used OSNAP and AUTOSNAP for drafting a rectangular table with arcs.
  * Used POLAR and ORTHO for drafting, exploring the main differences between them by drafting a square table.
  * Recreated the rectangular table with arcs using the circle, line, and the trim tool.

  <details>
  <summary> Geometry.dwg - Drawing Simple Geometry in an AutoCAD File </summary>
    
  > Geometry.dwg is the same previous floor plan used in the previous 2 modules.
  
  **Using zoom and pan for navigation**
  * Use the crosshairs to navigate the drawing and the mouse wheel to zoom in and out where the crosshairs lie.
  * Holding down the mousewheel reveals a hand which can be used to pan around the drawing.
  * Can also right click on the mouse to zoom or pan from the shortcut menu.
  * On the right hand side of the screen is the nav bar with a lot of zoom commands available.

  **OSNAP and AUTOSNAP**
  * Configured OSNAP for endpoint, midpoint, center, intersection and extension.
  * Ensured the layer was set to A-700-M_FFE, then used the rectangle tool in the draw panel to create a table.
  * Used [direct distance entry](https://github.com/ashthemech/AutoCAD-Learning/blob/d4a1ede4136bcbbdbbd4f815208c2aa3a0205f28/Drawing%20Simple%20Geometry/Direct%20Distance%20Entry.JPG) to size the table to 2500 by 1500 in metric millimeters.
  * Used the start, center, end arc tool to [add arcs](https://github.com/ashthemech/AutoCAD-Learning/blob/90a68354bfb13b356d9c2f7fe57e7e04d0fa5656/Drawing%20Simple%20Geometry/Arc%20Table.JPG) to the right and left of the table.
  * Used center, radius circle draw tool to draw a [600 metric mm circle in the center of the table](https://github.com/ashthemech/AutoCAD-Learning/blob/9b32ec50a54101f5e907216cd9c28d805412561a/Drawing%20Simple%20Geometry/Object%20snap%20tracking.JPG) using midpoint snap tracking of the rectangle.

  **POLAR and ORTHO**
  * Continuing in same layer, I made a 1500 metric mm by 1500 metric mm [table using the POLAR tracking](https://github.com/ashthemech/AutoCAD-Learning/blob/ef72715ab3da966c719fe9352d4eaca332f24ac5/Drawing%20Simple%20Geometry/polar%20tracking%20table.JPG) at 90 degrees with the line tool.
  * I repeated the process above, turning off POLAR tracking and this time using the ORTHO tracking with the line tool, restricting to lines only the x and y axis.
  * ORTHO is great for strictly horizontal and vertical drafting when that is necessary, while POLAR seems much more versatile with various angles.

  **Creating Lines, Arcs, and Circles**
  * Erased the square tables by selecting the 8 lines created, right clicking and erasing.
  * In the same layer, I recreated the [rectangular table](https://github.com/ashthemech/AutoCAD-Learning/blob/eb57c990ac8c1ecc78780616db0c6d546650dbe4/Drawing%20Simple%20Geometry/Circle%20and%20line%20table.JPG) earlier instead by using lines and 2 point circles with POLAR tracking and using quadrant snap.
  * To complete the table, I used the trim tool to [remove the inner semicircles](https://github.com/ashthemech/AutoCAD-Learning/blob/446693c4d9126fb902b7450081a33766eecc66cc/Drawing%20Simple%20Geometry/trimmed%20table.JPG), and added the center circle using [midpoint snapping](https://github.com/ashthemech/AutoCAD-Learning/blob/68454a31f4a5ae81162923005f5bf8c09da5fdaa/Drawing%20Simple%20Geometry/rectangular%20table%202.JPG).

  **Creating Polylines, Polygons and Splines**
  * Recreating the table as seen in the prevous section, but instead using the polyline tool.
  * I started by drawing the top line, entering 2500 metric mm, then right clicking and using the arc tool in the pop up menu at 1500 metric mm.
  * This was repeated for the bottom and left side, and the [table was again created](https://github.com/ashthemech/AutoCAD-Learning/blob/ad03c77413350e85a0ceca62c9d2b2c8813001d7/Drawing%20Simple%20Geometry/Polyline%20Table.JPG) wihtout the center circle.
  * I then added the inner circle to the table using the center, radius tool and setting to 650 mm for the [finished table](https://github.com/ashthemech/AutoCAD-Learning/blob/a8dfbc4b166bb43e094e7a7145fb3dd68f39082f/Drawing%20Simple%20Geometry/Polyline%20Table%20with%20Circle.JPG).
  * A 6 sided polygon was added using the polygon tool and inscribed in the circle of the table, then I erased the circle to have only the [polygon remaining](https://github.com/ashthemech/AutoCAD-Learning/blob/80065ebbaffea6c02efe6cc9da9a8fe2a6a9621f/Drawing%20Simple%20Geometry/Polyline%20Table%20with%20Polygon.JPG).
  * Ecplored the measurement tool in utilities to see how it can be used to measure distances within the drawing, measure the thickness of an adjacent wall to be 120.65mm.
  * Used the spline too to create a wavy line, then set the thickness using the offset tool to set the wavy line be the same thickness as the adjacent wall.
  * Then I used the line tool to complete the wall and the extend tool to extend the lower side of the wall to the [adjacent wall](https://github.com/ashthemech/AutoCAD-Learning/blob/438ced633edcc4f8303de62fc878fb61eeb35bfb/Drawing%20Simple%20Geometry/Wavy%20Wall.JPG).
  * Finally, I used the match properties tool to match the properties of the new wavy wall to the properties of the [existing walls](https://github.com/ashthemech/AutoCAD-Learning/blob/b23ef1366f28b58fe0d1f98299f3c86f1e0bf86f/Drawing%20Simple%20Geometry/Wavy%20Wall%20Property%20Match.JPG).
    
  </details>
</details>




