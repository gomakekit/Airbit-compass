## Note from MakeKit

This is an attempt to create an auto-correction of the Yaw-movement on the Air:bit drone.
The compass heading is compared to a desired compass heading, then the difference is being multiplied with a proportional (PID) number and set to Yaw.

* Challenge: The compass heading block uses the accelerometer in it´s equation. The accellerometer will give erradical numbers when motors are spinning. Therefore, these numbers needs to be smoothed with a low pass filter. 

The low pass filter and the compassCorrectionFactor needs to be adjusted.

## As time of writing (August 2020), the algorithm is not working



> Open this page at [https://gomakekit.github.io/airbit-compass/](https://gomakekit.github.io/airbit-compass/)

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/gomakekit/airbit-compass** and import

## Edit this project ![Build status badge](https://github.com/gomakekit/airbit-compass/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://makecode.microbit.org/](https://makecode.microbit.org/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/gomakekit/airbit-compass** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/gomakekit/airbit-compass/raw/master/.github/makecode/blocks.png)

#### Metadata (used for search, rendering)

* for PXT/microbit
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
