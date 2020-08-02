---
title: "Interactive Data Editor Reference"
layout: single
permalink: /ide_quick_refrence/
author_profile: false
toc: true
toc_sticky: true
classes: wide
---
fbefwebgweubgeugbeug 
HI tehre
<video  width="480" height="320" controls="controls">
  <source src="../videos/ide/3d_viewer.mp4" type="video/mp4">
</video>

# Documentation, Quick Reference and FAQs:
1. [Load data from file](#load-file) 
1. [3D Viewer](#3d-viewer)  
1. [Edit data](#edit-data)  
    1. [Drag with mouse](#drag-with-mouse)  
    1. [Move with keyboard](#drag-with-keyboard)  
    1. [Smooth with spline](#smooth-with-spline)  
    1. [Smooth with moving average](#smooth-with-mooving-average)  
    1. [Smooth with regression](#smooth-with-regression)  
    1. [Smooth multiple data simultaneously](#smoothing-multiple-datasets-simultaneously) 
    1. [Set required value](#set-required-value)  
    1. [Remove bad data](#remove-bad-data-points)  
1. [Interpolate data](#interpolate-data)
1. [Extend data, mirror or repeat](#extend-ata)
1. [Data fitting](#data-fitting)  
    1. [Polynomial regression](#polynomial-regressing-fitting)  
    1. [Lavenberg-Marquardett fitting](#lavenberg-marqardett-fitting)  
1. [Swap Data](#swap-data)  
1. [UnDo ReDo](#undo-redo)  
1. [Plot settings](#plot-settings)  
1. [Export plot as image](#export-as-image)  
1. [Work with spreadsheet](#work-with-spreadsheet)  
1. [Work 3D plotter](#work-with-the-3d-plotter)  




## Load File  
Directly load data from text file from `File > Open File`. For 3D data select the required `X/Y` value from the provied slider or scrolling inside the plot. If you want to add multiple data set from other files, you can load them through `File > Add File`. You can use the recent files menu to quickly load any of the last recent 10 files.
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/file_load.mp4" type="video/mp4">
</video>

## 3D Viewer  
For easy editing 3D data files, a 2D projection for a particular `X/Y` value. To view the complete 3D plot open the 3D viewer window through the `Window > 3D Plot Viewer`. The viewer updates in real time as you make updates in the main window.
![alt text](gifs/screenshot.gif "Screen shot")
<br/>
<div align="right">
    <b><a href="#documentation-quick-reference-and-faqs">↥ back to top</a></b>
</div>
<br/>

## Edit data  
This software features different data editing options, available to use thourgh keyboard shortcuts and also through the right click context menu  
### Drag with mouse  
Move any data points just dragging it mouse. By defualt data points is movable only in vertical direction (i.e. y-axis). Check the `Edit > Points movable horaizontally` to move them in x-axis too. To drag multiple data points simultaneously and drag any of them.  
![alt text](gifs/screenshot.gif "Screen shot")

### Drag with keyboard  
Select the required data points and move them using navigation on keyboard. This option is available only for mooving in y-axis
![alt text](gifs/screenshot.gif "Screen shot")

### Smooth with spline
Select data points that you want to smooth and press `D`. The data points will be replaced with a smoothing spline approximation  
![alt text](gifs/screenshot.gif "Screen shot")

### Smooth with mooving average
Press `M` after selecting data points to apply an moving average over them.
![alt text](gifs/screenshot.gif "Screen shot")


### Smooth with regression
Replace data points with a quadratic regressing approximation by pressing `E`
![alt text](gifs/screenshot.gif "Screen shot")


### Smoothing multiple datasets simultaneously  
At any moment all data editing feature is only available for a single dataset. But the primary dataset for edit can be quickly toggled through the `Plot utility` button or by pressing `Ctrl+TAB`
![alt text](gifs/screenshot.gif "Screen shot")

### Set required value  
![alt text](gifs/screenshot.gif "Screen shot")

### Remove bad data points  
![alt text](gifs/screenshot.gif "Screen shot")

## Interpolate data 
Use interpolation to fill missing grid values or make the grid denser or vice-versa through `Edit > Fill values`  
![alt text](gifs/screenshot.gif "Screen shot")

## Extend Data
Extend your dataset by repeating or mirroring. This can be applied globally  
![alt text](gifs/screenshot.gif "Screen shot")

or locally  
![alt text](gifs/screenshot.gif "Screen shot")

## Data fitting  
(Only) 2D data set can be fitted thorugh two types of fitting  
### Polynomial regressing fitting  
Use `Fitting > Polynomial Regression fitting`
![alt text](gifs/screenshot.gif "Screen shot")

### Lavenberg-Marqardett fitting  
Use `Fitting > Lavenberg-Marqardett fitting`


## Swap data
To swap data values between two data sets open swapper mode by `View > Toggle Swapper`  
![alt text](gifs/screenshot.gif "Screen shot")

## UnDo ReDo
You can undo or redo last 10 changes by pressing `Ctrl+Z` or `ShiftCtrl+Z`  
![alt text](gifs/screenshot.gif "Screen shot")

## Plot settings
To make any changes to the plot option/style like marker/line styles, font styles, open the setting window `View > Open Plot Settings`  
![alt text](gifs/screenshot.gif "Screen shot")

## Export as image
Save your plot in different format and resolution. Use `File > Export as image` or the camera sign on the plot corner  
![alt text](gifs/screenshot.gif "Screen shot")

## Work with spreadsheet  
Open a spreadsheet containing the current data set through `Window > Spreadsheet`. You can directly make changes to the data set  
![alt text](gifs/screenshot.gif "Screen shot")

## Work with the 3D Plotter  
A 3D plotter is also provided to quickly plot 3D data sets  
![alt text](gifs/screenshot.gif "Screen shot")

