# Darktable website banners #

## Introduction ##
This repository contains marketing material for the open source software Darktable. Currently we have web banners in common image dimensions used in advertising campaigns.

## Guide ##
### Folder structure ###
- Assets: Resources used during the image generation process but not are essentially
- Export: Exported images, final result
- Source: Source files to edit

### File names ###
Naming convention:

    (Theme name)_(x-dimension 3-digits)_(y-dimension 3-digits)_(banner name)_(alternative number)_(Alternative name)
Example: SimpleApp_088_031_Button_v01_Slogan.svg

Notes:

- Alternative number and alternative name are only needed if two or more alternatives for a specific resolution 
- Leading digits ('031' instead of '31') are needed for proper file display and ordering


### Inkscape setup ###


### Hints ###
- Exported PNG's from Inkscape look a bit blurry,
- With a decent text editor that is capable of search and replace over multiple files you can change 

### Inkscape setup ###
Since Inkscape is vector-based and I need pixel sizes I setup Inkscape as follows:

- Set dimensions to pixels: **'Edit'** -> **'Preferences'** -> **'Interface'** -> **'Grids'** -> set both **'Rectangular grid'** and **'Axonometric grid'** to **'px'**
- **'Edit'** -> **'Preferences'** -> **'Bevahiour'** -> **'Steps'** -> Set all options to **'px'**, for more precise adjustmens reduce movements to 1px
- **'File'** -> **'Document properties'** -> **'Page'** -> **'Custom size'** -> Units: **'px'**
- **'File'** -> **'Document properties'** -> **'Grids'** -> **'New'** grid -> **'Grid units'** set to **'px'** (since this setup is set for the current document I recommend creating new banners as copies from the current one)
