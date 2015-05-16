<!--Copyright:
Nico Rikken, 2015
-->

# power-system-shapes
Collection of Power System Shapes for multiple editors

## Goal
The goal of this project is to provide a collection of power system shapes free to use and incorporate in other software. Most available free diagramming software solutions lack a power system shape collection. Some even lack more generic electrical symbols. This project is an attempt to change that.

The goal can be defined along two axis, namely the number of targeted applications and the number of shapes.

## Process
As different applications have different needs in terms of file formats, the shapes will be generated from a set of base definitions. In this way support for other applications can be added relatively easy if needed.

## Licence
These shapes are available under the GPLv2, to allow inclusion with Dia. If you desire a different licence for inclusion in your free software project, please contact me.

## Targeted software
There are multiple projects which would benefit from a collection of power system shapes:
 1. Dia (via sheets)
 2. LibreOffice Draw (via a plugin)
 3. LibreCAD
 4. QCad
 5. Inkscape (more general)

## Shape resources
Power system symbols have existed for many years and are standardized by multiple international standards. As a result most symbols are widely available in standards documents, books, manuals and academic papers. Despite standardisation symbols might vary slightly between countries and a further distinction can be made between symbols depicting all phases and single-line diagram (SLD) variants.

* IEC-60617 (Graphical symbols for diagrams)
* IEC 81714 (Designing of symbols)
* IEC 61082 (about drawing electrical diagrams)
* LibreCAD libraries http://wiki.librecad.org/index.php/Part_Libraries

## Progress log
* late 2014: Initial work for Dia.
* spring 2015: Refactoring of previous symbols and additions to create a base set.

## Bugs (todo)
* Shape renaming
* Additional shapes
* Extra outlines for better aligment (like the Electrical set for Dia)
* (Automatically) convert Dia shapes to svg, png, etc.
