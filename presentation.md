Color Image Processing
========================================================
author: Raghuveer Kanneganti
date: 11-22-2015

Goal and Introduction
========================================================

Goal:
The goal of this presentaion is to introduce the new Shiny App that's build as a part of the Coursera's Developing Data Products course project

Introduction: Image processing is the process of adjusting digital images so that the results are more suitable for display or further image analysis. For example, you can remove noise, sharpen, or brighten an image, making it easier to identify key features.

Image processing
=========================================================
Any color is a combination of Red, Green and Blue primary colors. 

One can adjust/tweak the color image by maniuplation of the Red, Green and Blue pixel values. In other words every pixel value is a combination of Red, Green and Blue values. So they can be manipulated to change the look of an image


Mathematical explanation
========================================================
For example if one of the pixel value is (Red = 150, Green = 175 , Blue =200)

One can brighten the pixel by adding an arbitary value to it 

```r
Rval = 10; Gval = -12; Bval = 20 
150 + Rval ; 175 + Gval ; 200 + Bval
```

```
[1] 160
```

```
[1] 163
```

```
[1] 220
```

Similarly change in contrast can be produced by multiplying a number to the pixel values and Gamma correction by taking the power of the pixel values to an arbitary number

Summary
=========================================================

A shiny tool is developed to interpret the effect of changing the parameters by observing the changes in the input image in near real-time.

Application: https://wida.shinyapps.io/DevelopingDataProducts
