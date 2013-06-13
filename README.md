Ocean Wave Effector for CINEMA 4D
==============

#[Download](http://bit.ly/11bpqMU)

![Ocean Wave Screenshot](https://raw.github.com/CreativeTools/ct-ocean-waves/master/screenshot.png)

###[Video](https://vimeo.com/65721379)

###Note

Note that this script only works with CINEMA 4D-versions _Studio_ and _Broadcast_.
It has only been tested in CINEMA 4D R14.

##File contents

The C4D file contains two objects:
* Plane
  * CT Wave Effector

_CT Wave Effector_ is responsible for the wave-like movement, the plane can be replaced by any object

##Usage
Move and rotate the _CT Wave Effector_ object to influence the points and create wave-like motion. See the video for an overview.

##Settings
The _CT Wave Effector_ object has a number of settings in the _User Data_ tab.

* Twist Amount
  * Controls the size of the waves
* Width
  * The distance from the effector at which points are still influenced by the deformation. Combine with *Twist Amount* to control the size of the waves.
* Falloff
  * The way the distance from the effector affects the deformation of the points. Used to create a smooth transition between wave and "calm" sea
* Texture
  * A grayscale 2D texture applied to the wave, influencing the *Twist Amount*.
* Texture Offset
  * A positional offset of the *Texture*. Animate to create a sense of motion in the wave.
* Bend
  * Bends the wave around the Axis Center of the deformed object. Can be used to create splashes or boat wakes.

##Inspiration
This script was inspired by, and backwards-enginered from, the wave tool in [this video](https://vimeo.com/4697942).

##CG News
Visit the Creative Tools blog for your daily dose of CG news.
###[English](http://translate.google.com/translate?js=n&sl=auto&tl=en&u=http://www.creativetools.se/blog/)
###[Swedish](http://www.creativetools.se/blog/)
