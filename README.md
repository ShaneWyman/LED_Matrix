## Members
Shane Wyman, Computer Engineering Student (2027)
shanew05@vt.edu

## Mentor
MENTOR NAME HERE

## Current Status
IN PROGRESS

## Project Overview

The project will be a LED matrix set up a grid pattern of 32 x 18 (576 total LEDs) with 3d printed seperating boxes in between each LED which is then funneled into a light diffusing fabric. With the current parts, the LED matrix will be about 2ft by 1ft. This will all be controlled with a Arduino Mega with the fastLED libary, as it will be responsible for the LED activation along with some rendering. In order to reach the required current to run 576 LEDs, a external power supply will be used. The base of the grid pattern will first be setup on a piece of cardboard, the strips will be glued on, tested, then the 3d printed boxes, then finally the light diffusing fabric will be wrapped around.

## Educational Value Added

The main one is the simple fact that I've never really had the free reign to work on a project of this scale, most times it is either heavly group influenced or not nearly to a large enough scale. The other educational values are a further understandings of using arudino libaries, 3d printing parts, high current DC circuts. I also plan on using the arudino to render some gifs, from things as simple as a dot bouncing around the screen to things like audio visuallizers and more.

## Tasks

1st: Verifcation of theroy: Need to make sure the libary and such work, as the testing will invovle 1 LED being on at any given moment, the arudiono can run it by itself without needing the power supply.
2nd: Build matrix: Cut up LEDs into strips of 32 and glue them to the cardboard, wire them up together and test 1 LED when all. After that wire up power supply and then test max current.
3rd: Do all the testing, properly set up the matrix and testing different screens and some renders.
4th: Glue on the 3d parts, wrap in light diffusing fabric, and mount it up on a wall or something.
5th: Extra stuff can be done like make more programs and screens to have diffrent effects shown.

## Design Decisions

1. Project can be done with just a standard Uno r3 with 2kb of ram, but I want the mega with 4kb of ram. The main reason stems to that I want the arudino to being doing more than just sending out the data to all the LEDs. I want to possibly run an audio visualizer on it, some fractals, maybe setup a webserver to send it data from a computer for it to display. Having a mega would allow more to be done in about the same size package.

## Design Misc

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Steps for Documenting Your Design Process

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## BOM + Component Cost

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Timeline

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Useful Links

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->

## Log

<!-- Your Text Here. You may work with your mentor on this later when they are assigned -->
