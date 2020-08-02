---
title: "Interactive Data Editor Reference"
layout: single
permalink: /ide_quick_refrence/
author_profile: false
toc: true
toc_sticky: true
---

<!-- 
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
 -->



## Load File  
Directly load data from text file from `File > Open File`. For 3D data select the required `X/Y` value from the provied slider or scrolling inside the plot. If you want to add multiple data set from other files, you can load them through `File > Add File`. You can use the recent files menu to quickly load any of the last recent 10 files.
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/file_load.mp4" type="video/mp4">
</video>

## 3D Viewer  
For easy editing 3D data files, a 2D projection for a particular `X/Y` value. To view the complete 3D plot open the 3D viewer window through the `Window > 3D Plot Viewer`. The viewer updates in real time as you make updates in the main window.
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/3d_viewer.mp4" type="video/mp4">
</video>


## Edit data  
This software features different data editing options, available to use thourgh keyboard shortcuts and also through the right click context menu  
### Move with mouse or keyboard  
Move any data points just dragging it mouse. By defualt data points is movable only in vertical direction (i.e. y-axis). Check the `Edit > Points movable horaizontally` to move them in x-axis too. To drag multiple data points simultaneously and drag any of them. Also keyboard navigation keys can also be ued to move selected data points. Although this option is available only for mooving in y-axis.

<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/edit_data.mp4" type="video/mp4">
</video>


### Smooth with spline
Select data points that you want to smooth and press `D` or `M` or `E` to replace the data points with a smoothing spline approximation or moving average or by quadratic regression respectively. Bad data points can also be romeved or set by required value
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/data_edit_2.mp4" type="video/mp4">
</video>



### Smoothing multiple datasets simultaneously  
At any moment all data editing feature is only available for a single dataset. But the primary dataset for edit can be quickly toggled through the `Plot utility` button or by pressing `Ctrl+TAB`

<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/mulit_edit.mp4" type="video/mp4">
</video>


## Interpolate data 
Use interpolation to fill missing grid values or make the grid denser or vice-versa through `Edit > Fill values`  
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/interpolate.mp4" type="video/mp4">
</video>

## Extend Data
Extend your dataset by repeating or mirroring. This can be applied globally  
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/extend.mp4" type="video/mp4">
</video>

or locally  
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/mirror_2.mp4" type="video/mp4">
</video>

## Data fitting  
(Only) 2D data set can be fitted thorugh two types of fitting  
### Polynomial regressing fitting  
Use `Fitting > Polynomial Regression fitting`
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/rgfit.mp4" type="video/mp4">
</video>

### Lavenberg-Marqardett fitting  
Use `Fitting > Lavenberg-Marqardett fitting`
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/lmfit.mp4" type="video/mp4">
</video>

## Swap data
To swap data values between two data sets open swapper mode by `View > Toggle Swapper`  
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/swapper.mp4" type="video/mp4">
</video>

## UnDo ReDo
You can undo or redo last 10 changes by pressing `Ctrl+Z` or `ShiftCtrl+Z`  
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/undo-redo.mp4" type="video/mp4">
</video>

## Plot settings
To make any changes to the plot option/style like marker/line styles, font styles, open the setting window `View > Open Plot Settings`  
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/settings.mp4" type="video/mp4">
</video>

## Export as image
Save your plot in different format and resolution. Use `File > Export as image` or the camera sign on the plot corner  
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/export.mp4" type="video/mp4">
</video>

## Work with spreadsheet  
Open a spreadsheet containing the current data set through `Window > Spreadsheet`. You can directly make changes to the data set  
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/spreadsheet.mp4" type="video/mp4">
</video>

## Work with the 3D Plotter  
A 3D plotter is also provided to quickly plot 3D data sets  
<video width="1000" height="510" controls="controls">
  <source src="../videos/ide/plotter.mp4" type="video/mp4">
</video>

