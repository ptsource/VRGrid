# Virtual Space modelling

Ad hoc models, or sketch models, are sometimes made to study the interaction of volumes, different viewpoints, or concepts during the design process.
Presentation models can be used to exhibit and visualise final design. A model are also used as show pieces, for instance as a feature in the reception of a building, or as part of a museum exhibition such as scale replicas of historical buildings.

# VRGrid & Virtual reality
### Current version 9 released 16/06/2019 compiled and tested under Windows 10

Virtual reality (VR) is an interactive computer-generated experience taking place within a simulated environment. It incorporates mainly auditory and visual feedback, but may also allow other types of sensory feedback like haptic. This immersive environment can be similar to the real world or it can be fantastical. Augmented reality systems may also be considered a form of VR that layers virtual information over a live camera feed into a headset or through a smartphone or tablet device giving the user the ability to view three-dimensional images. VRGrid is an XML standard based markup language for representing interactive 3D and 2D with VR support. It includes its own scripting language for software design, and a format support for 3D models. The design goals of XML emphasize simplicity, generality, and usability across the Internet. It is a textual data format with strong support via Unicode for different human languages.

[![Maintenance](/images/maintained.svg)]() [![Travis](/images/rust.svg)]()  [![You can download here.](/images/version-9-red.svg)](https://dl.orangedox.com/tX6IL0ZzYy6z5vI2sE?dl=1)  [![You can download here.](/images/download-here-green.svg)](https://dl.orangedox.com/tX6IL0ZzYy6z5vI2sE?dl=1) [![Help here.](/images/docs-here-blue.svg)](https://wiki.ptsource.eu/)

# VRGrid Rendering

VRGrid uses Microsoft DirectX SDK (runtimes included in the installer) , Oculus Rift SDK and Hillcrest Labs Freespace SDK for its rendering . Rendering for interactive media, such as simulations, is calculated and displayed in real time, at rates of approximately 20 to 120 frames per second. In real-time rendering, the goal is to show as much information as possible as the eye can process in a fraction of a second (a.k.a. "in one frame": In the case of a 30 frame-per-second animation, a frame encompasses one 30th of a second).

# VRF File format

The VRF format uses standard XML developed by the World Wide Web Consortium along with the Powers & Stephens parsers for XML. The design goals of XML emphasize simplicity, generality, and usability across diferent platforms. It is a textual data format with strong support via Unicode for different human languages. 

# VRI Image format

VRI image format only displays in VRGrid. VRI image format supports palette-based images (with palettes of 24-bit RGB or 32-bit RGBA colors), grayscale images (with or without alpha channel for transparency), and full-color non-palette-based RGB/RGBA images (with or without alpha channel) converted from PNG or APNG high resolution format.

## Screenshots

![PTSource VRGrid](https://raw.githubusercontent.com/ptsource/VRGrid/master/images/01.PNG)![PTSource VRGrid](https://raw.githubusercontent.com/ptsource/VRGrid/master/images/02.PNG)![PTSource VRGrid](https://raw.githubusercontent.com/ptsource/VRGrid/master/images/03.PNG)
![PTSource VRGrid](https://raw.githubusercontent.com/ptsource/VRGrid/master/images/04.PNG)![PTSource VRGrid](https://raw.githubusercontent.com/ptsource/VRGrid/master/images/05.PNG)![PTSource VRGrid](https://raw.githubusercontent.com/ptsource/VRGrid/master/images/06.PNG)

## Features

* Cloud based VRF(xml) files
* Native VR support
* Github hosting support for team management
* Integrated speech engine
* Integrated HTML support
* Integrated Media support
* Custom VRI Texture format
* PHP & MYSQL Get and Post support
* ... and much more

## VRModes supported

* Side by Side
* DIY Rift
* Oculus Rift DK1
* Anaglyph (Red/Cyan)
* Anaglyph (Yellow/Blue)
* Anaglyph (Green/Magenta)

## Trackers supported

* Memory Tracker
* Hillcrest Labs Tracker
* FreeTrack Tracker




