ai-svg-export
=============

Simple-but-tricky script that exports each layer of an Adobe Illustrator to separate svg files (1 layer => 1 .svg)

Instructions of use
===================

A) If you use an existing file, ensure each element you'd like to be exported as svg is one unique layer. If not, then you'll have to fix it first (manually). Any script automating this task would be appreciated 
B) If you are likely to create a file from scratch then export its elements, then keep in mind building a single layer for every single element. Merging every element in the layer might help. 

1) Open your file 
2) Depending on your version of Illustrator, go to File / Scripts / Import Script 
3) A dialog box will open. At this step of development (almost null), the select menu has "svg" selected by default, but the options are JPG options. Just switch the select to "JPG" then back to "SVG" and you're done (if you can fix this, push !) 
4) Choose a folder where to put the svgs (and also a script that should repeat the process. Honestly I didn't try it) 
5) Cross fingers while having a look at the selected export folder. 
6) Works ? Great !! Doesn't ? Find why in Adobe's Documentation (I'm too busy for that ATM :o) 