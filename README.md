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
  * Learned how to use the polyline and polygon tool by recreating a version of the previous rectangular table and how to use spline tool and match properties by creating a wavy wall.
  * Completed the challenge objective to create a table with a circular insert using polyline and circle tools.
  * Took the Simple Geometry Quiz, 6/7 then retook and 7/7.

  <details>
  <summary> Geometry.dwg - Drawing Simple Geometry in an AutoCAD File </summary>
    
  > Geometry.dwg is the same floor plan used in the previous 2 modules.
  
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
  * Recreating the table as seen in the previous section, but instead using the polyline tool.
  * I started by drawing the top line, entering 2500 metric mm, then right clicking and using the arc tool in the pop up menu at 1500 metric mm.
  * This was repeated for the bottom and left side, and the [table was again created](https://github.com/ashthemech/AutoCAD-Learning/blob/ad03c77413350e85a0ceca62c9d2b2c8813001d7/Drawing%20Simple%20Geometry/Polyline%20Table.JPG) wihtout the center circle.
  * I then added the inner circle to the table using the center, radius tool and setting to 650 mm for the [finished table](https://github.com/ashthemech/AutoCAD-Learning/blob/a8dfbc4b166bb43e094e7a7145fb3dd68f39082f/Drawing%20Simple%20Geometry/Polyline%20Table%20with%20Circle.JPG).
  * A 6 sided polygon was added using the polygon tool and inscribed in the circle of the table, then I erased the circle to have only the [polygon remaining](https://github.com/ashthemech/AutoCAD-Learning/blob/80065ebbaffea6c02efe6cc9da9a8fe2a6a9621f/Drawing%20Simple%20Geometry/Polyline%20Table%20with%20Polygon.JPG).
  * Explored the measurement tool in utilities to see how it can be used to measure distances within the drawing, measuring the thickness of an adjacent wall to be 120.65mm.
  * Used the spline too to create a wavy line, then set the thickness using the offset tool to set the wavy line be the same thickness as the adjacent wall.
  * Then I used the line tool to complete the wall and the extend tool to extend the lower side of the wall to the [adjacent wall](https://github.com/ashthemech/AutoCAD-Learning/blob/438ced633edcc4f8303de62fc878fb61eeb35bfb/Drawing%20Simple%20Geometry/Wavy%20Wall.JPG).
  * Finally, I used the match properties tool to match the properties of the new wavy wall to the properties of the [existing walls](https://github.com/ashthemech/AutoCAD-Learning/blob/b23ef1366f28b58fe0d1f98299f3c86f1e0bf86f/Drawing%20Simple%20Geometry/Wavy%20Wall%20Property%20Match.JPG).

  **Challenge**
  Create a polyline with an arc segment and add a circular insert to it to create [another table](https://github.com/ashthemech/AutoCAD-Learning/blob/8a1c12203fe66cf7ec3580c18ab7a22e9f66aa0f/Drawing%20Simple%20Geometry/Challenge%20Table.JPG) in the office layout.
  * I used the polyline tool to start at the left side of the table with a vertical line of 2000 mm.
  * I completed the bottom of the table by drawing another line and using direct entry to a length of 2500mm.
  * Switching to the arc polyline tool with the mouse menu I made the righthand arc, then completed the table shape by switching again to line and [closing the shape](https://github.com/ashthemech/AutoCAD-Learning/blob/660843c203e19f85714dd383ec3a4e2990bebde4/Drawing%20Simple%20Geometry/My%20Challenge%20Table.JPG).
  * Then I used the center, radius tool to create the circular insert and set the radius to 700mm, confirming the specifications with the [measure tool](https://github.com/ashthemech/AutoCAD-Learning/blob/79c61c57690bdce160be6051f0ad95797453fe31/Drawing%20Simple%20Geometry/My%20Challenge%20Table%20Complete.JPG).

  </details>
</details>

<details>
<summary> 4. Annotating Simple Designs </summary>

  Key Takeaways:
  * Learned how to create new text styles in the annotate tab in the home ribbon, creating Dims_MODEL and Labels_MODEL_300mm.
  * Learned how to use the multiline text box and single line text box and add a background mask.
  * Learned how to navigate the Dimension Style Manager and New Dimension Style dialogue boxes when creating a new dimension style.
  * Placed dimension annotations to the conference table, setting the appropriate scale from the viewport and setting the override dim layer.
  * Placed leaders for the chair and hexagonal insert in the conference table using the QLEADER tool.
  * Completed the challenge to resize the dimension text.
  * Completed the chapter quiz, 5/5.

<details>
<summary> Annotation.dwg - Annotating Simple Designs in AutoCAD </summary>
  
   > Annotation.dwg is the same floor plan used in the previous 3 modules.

  **Working with Text Styles**
  * Need a way to add text annotation and dimension annotation to designs in dwg files, using "styles".
  * Encompasses labels, notes, anything to communicate design intent and making sure we are on the appropriate layer.
  * Can use the home ribbon and pin the annotate flyout, or use the annotate ribbon and open the text dialog box.
  * In the text style dialog box, I clicked "new" and named it Dims_MODEL (note, there are naming conventions based on standard procedures for workflows).
  * I changed the font type to Calibri and left height at 0 (AutoCAD will ask for the height when placing text).
  * repeated the process for the Labels_MODEL_300mm, but this time the height was specified to 300mm.

  **Single Line Text and Multiline Text**
  * Created a new layer to place text called "text" and changed the color to red.
  * Used multiline text option and specified an area for the text to be placed by drawing a rectangle, which opened the text editor tab on the ribbon.
  * Added a background mask with the color cyan, and also bolded and italicized the text reading ["Large Conference Room CONF123"](https://github.com/ashthemech/AutoCAD-Learning/blob/fbdc673c78522b9af10647fa8c66690347157ae0/Annotating%20Simple%20Designs/CONF123%20text.JPG).
  * Added a single line text, justifiied to the center of the conference table to label the table as ["Large Conference Table"](https://github.com/ashthemech/AutoCAD-Learning/blob/90f05600f5adeb12d603660e969b2d9216a76a15/Annotating%20Simple%20Designs/CONF123%20Table%20Label.JPG).

  **Creating Dimension Styles**
  * Creating an effective dimension style is similar to adding labels, but with more parameters.
  * Opened the Dimension Style Manager dialog box and created a new Dimension Style names "Training_ANNO", using LinkedIn_Learning as the "Start With" option.
  * Substyles can also be created for specific dimension types, but “all dimensions” was selected for this training.
  * Explored the tabs in the New Dimension Style dialog box like tolerances, alternate units, etc.
  * Ensured Dimension and Extension Lines were all set to "By Layer" to make sure it adopts the layer properties, and set Baseline Spacing to 12mm.
  * Set the First and Second arrowheads to "Closed filled" in the Symbols and Arrows tab.
  * In the text tab, set the "text style" to the created Dims_MODEL, and in the Primary Units tab the Decimal format is set with a precision of 0.

  **Placing Dimensions**
  * Ensured I was on the "A-010-D_DIM" layer and the annotation style was the newly created "Training_ANNO" before continuing.
  * Learned how to set the Dims Layer Override in the Annotation ribbon, which overrides the current layer if style is set to annotation.
  * Since the dimension style is annotative, it needs an annotation scale in the model that reflects scale in the layout tab.
    * Went to the ISO A-1 landscape tab and checked that the viewport scale is 1:100, meaning this view is 100th of the size in the model tab.
    * Went to status bar in model tab, and adjusted the scale to match the viewport.
    * This tells AutoCAD that anything placed in the annotative style will be scaled accordingly in the viewport.
  * Added a linear dimension and a radius dimension to the [conference table](https://github.com/ashthemech/AutoCAD-Learning/blob/62faf78efa7e3fdbd18aeabb0e91e3399f4d6aaa/Annotating%20Simple%20Designs/Conference%20Table%20with%20Dimensions.JPG) in the conference room using the created dimension style.

  **Adding Leaders (QLEADER)**
  * Note, Dim Layer override does not work with QLEADER!
  * QLEADER command is in the dynamic input, so when you type it pops up.
  * Set the endpoint to be the midpoint of a conference chair, and typed "Chair" into the text box.
  * Repeated this process for the hexagon in the center of the [table](https://github.com/ashthemech/AutoCAD-Learning/blob/0f5fb5bb28c0008e1a6bc347279c5258967f6745/Annotating%20Simple%20Designs/QLEADER.JPG).

  **Challenge**
  
  Make the previous dimension text placed look smaller (2.5mm) in the drawing, and leave the QLEADER labels the same previous size.
  
  * To complete this challange, I opened the Annotations tab in the home ribbon and opened the dimension style dialogue box.
  * I then changed the preset height in the "Text" tab by clicking "Modify" on the "Training_ANNO" text style, from [4.5mm to 2.5mm](https://github.com/ashthemech/AutoCAD-Learning/blob/a8ba2c89721f3a9be345eb99aa4e0dcfb9e39cf9/Annotating%20Simple%20Designs/Dimension%20Label%20Challange.JPG).

</details>
</details>

<details>
<summary> 5. Communicating Design Intent </summary>

  Key Takeaways:
  * blah

<details>
<summary> Communicating.dwg - Commnicating Design Intent in AutoCAD </summary>

  > Communication.dwg is the same floor plan used in the previous 4 modules.

  **Creating a Title Block**
  * Communicating design intent is extremely important in the industry - sizes, what is your design?
  * This is how I want my design to look, be built, be manufactured, etc.
  * Normally, you develp a page setup and a specific title block for the drawings but here we use a "cheat" tite block for clarity and speed.
  * Went into the ISO A-! Landscape sheet and ensured I was on the title block layer.
  * Added a rectangle using the drawing tool in the title block layer, ensuring to stay wihtin the dashed lines so nothng is truncated.
  * Created a new annotation text style called "Title_LAYOUT_15mm" and added a title of ["Office Floor Plan - GENERAL LAYOUT"]() in the "Titletext" layer.
  
</details>
</details>




