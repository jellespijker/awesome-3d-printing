<div align="center">
	<img width="500" height="350" src="media/logo.svg" alt="Awesome">
	<br>
	<p>
		<p>
			<sup>
				<a href="https://github.com/jellespijker">My profile</a>
			</sup>
		</p>
		<br>
	</p>
</div>

<p align="center">
	<a href="contributing.md">Contribution guide</a>&nbsp;&nbsp;&nbsp;
</p>

## Contents

- [Contents](#contents)
- [Software](#software)
  - [Slicers](#slicers)
    - [Cura plugins](#cura-plugins)
  - [Libraries and Tools](#libraries-and-tools)
    - [Toolpath - Generator](#toolpath---generator)
    - [Toolpath - Interpreter](#toolpath---interpreter)
    - [Toolpath - Misc](#toolpath---misc)
    - [Toolpath - PostProcessing](#toolpath---postprocessing)
    - [Packing and Arranging](#packing-and-arranging)
- [Hardware](#hardware)
  - [Printers](#printers)
  - [Firmware](#firmware)
  - [CAD](#cad)

## Software

### Slicers

- [Cura](https://ultimaker.com/nl/software) - The world's most popular 3D printing software.
  - [Repo](https://github.com/Ultimaker/Cura) - Source code
  - [plugins](#cura-plugins)
- [Cura-lulzbot](https://www.lulzbot.com/cura) - Cura LulzBot Edition for LulzBot 3D Printers by Aleph Objects, Inc
- [Cura-BCN3D](https://github.com/BCN3D/Cura) - 3D printer / slicing GUI built on top of the Uranium framework, customized for the BCN3D machines
- [Pathio](https://pathio.xyz/) - A modern slicer for extrusion 3D printing provided by E3D Skunkworks
- [Slic3r](https://slic3r.org/) - Open Source toolpath generator for 3D printers
  - [Repo](https://github.com/slic3r/Slic3r) Source code
- [PrusaSlicer](https://www.prusa3d.com/prusaslicer/) - a feature-rich, frequently updated tool that contains everything you need to export the perfect print files for your Original Prusa 3D printer.
  - [Repo](https://github.com/prusa3d/PrusaSlicer)
- [SuperSlicer](https://github.com/supermerill/SuperSlicer) - G-code generator for 3D printers (Ultimaker, Prusa, Voron, Creality, etc.) Fork of Prusa Slicer.
- [FlashPrint](https://www.flashforge.com/software/detail/Flashprint?id=40) - Slicer for the FlashForge 3D printers.
- [chitubox](https://www.chitubox.com/download.html)  - All-in-one SLA/DLP/LCD Slicer. A free 3D printing slicer software to help you design and slice you objects.
- [IceSL](https://icesl.loria.fr/) - A GPU accelerated modeler and slicer for 3D printing
- [Ideamaker](https://www.raise3d.com/ideamaker/) - Fast and user friendly 3D slicer for FDM printers
- [KISSlicer](http://www.kisslicer.com/index.html) - KISSlicer is a fast, easy-to-use, cross-platform program that takes 3D files (STL) and generates path information (G-code) for a 3D Printer. The FREE version has all the features needed for the hobbyist who uses a single-head machine
- [Mattercontrol](http://www.mattercontrol.com/) - Software solution for 3D printers
  - [Repo](https://github.com/MatterHackers/MatterControl) Source code
- 

#### Cura plugins

- [CuraOrientationPlugin](https://github.com/nallath/CuraOrientationPlugin) - CuraOrientation plugin is a simple wrapper around the STL-tweaker
- [BabarianPlugin](https://github.com/nallath/BarbarianPlugin) - A plugin to convert barbarian scaled models to metric.
- [cura-camera-position](https://github.com/Ultimaker/cura-camera-position) - Position the camera in a specific place to see the build plate always from the same perspective.
- [SettingsGuide](https://github.com/Ghostkeeper/SettingsGuide) - More extensive explanation of Cura slicing settings
- [cura-god-mode-plugin](https://github.com/sedwards2009/cura-god-mode-plugin) - Plugin to make debugging settings problems much easier
- [cura-big-flame-graph](https://github.com/sedwards2009/cura-big-flame-graph) Big Flame Graph profile plugin for Cura
- [Cura-OctoPrintPlugin](https://github.com/fieldOfView/Cura-OctoPrintPlugin) - Cura plugin which enables printing directly to OctoPrint and monitoring the process
- [Cura-ZOffsetPlugin](https://github.com/fieldOfView/Cura-ZOffsetPlugin) - A Cura plugin that adds a Z Offset setting
- [Cura-SidebarGUIPlugin](https://github.com/fieldOfView/Cura-SidebarGUIPlugin) - A Cura plugin that provides a more settings-centric GUI for those who prefer it
- [Cura-MeshTools](https://github.com/fieldOfView/Cura-MeshTools) - Cura plugin which adds several mesh analysis and manipulation tools
- [Cura-MeasureTool](https://github.com/fieldOfView/Cura-MeasureTool) - Cura plugin which adds a tool for measuring parts of models
- [Cura-SimpleShapes](https://github.com/fieldOfView/Cura-SimpleShapes) - A Cura plugin that adds simple shapes (cube, sphere, cylinder)

### Libraries and Tools

#### Toolpath - Generator

- [CuraEngine](https://github.com/Ultimaker/CuraEngine) - A powerful, fast and robust engine for processing 3D models into 3D printing instructions, written in C++
- [MatterSlice](https://github.com/MatterHackers/MatterSlice) - a C# console application that generates GCode (hardware control) for 3D printing. It was originally ported from CuraEngine (another great open source 3D printing engine). It is the primary slicing engine for MatterSlice and under constant development.
- [opencamlib](https://github.com/aewallin/opencamlib) - open source computer aided manufacturing algorithms library, written in C++
- [PyCAM](http://pycam.sourceforge.net/) - a toolpath generator for 3-axis CNC machining. It loads 3D models in STL format or 2D contour models from DXF or SVG files. The resulting G-Code can be used with LinuxCNC or any other machine controller. Written in Python
- [CamMill](https://github.com/cammill/cammill) - CAM application to produce tool paths and gcode from DXF files, written in C

#### Toolpath - Interpreter

- [GHermeneus](https://github.com/Ultimaker/GHermeneus) - a fast GCode interpreter and parser, written in C++20
- [gcode3d](https://github.com/patrickelectric/Gcode3D) - GCode visualizer
- [yagv](https://github.com/jonathanwin/yagv) - A fast 3D Gcode Viewer for Reprap-style 3D printers, in Python and OpenGL

#### Toolpath - Misc

- [Universal-G-Code-sender](https://github.com/winder/Universal-G-Code-Sender) - A Java based GRBL compatible cross-platform G-Code sender.
- [RepRaptor](https://github.com/NeoTheFox/RepRaptor) - A Qt RepRap gcode sender/host controller
- [Pronterface](https://github.com/kliment/Printrun) - Pronterface, Pronsole, and Printcore - Pure Python 3d printing host software
- [3delta](https://github.com/minad/3delta) - 3Δ is a host software for 3d printers of the delta style. In many aspects it is similar to Pronterface. However it brings additional motion control better suited to non-cartesian delta printers.

#### Toolpath - PostProcessing

- [GPX](https://github.com/markwal/GPX) - Gcode to x3g conversion post processor, written in C
- [AutoLevellerAE](http://www.autoleveller.co.uk/) - Java based software for 'levelling' GCode file for use on a CNC machine
  - [Repo](https://bitbucket.org/daedelus1982/autolevellerae/src/master/) - Source code

#### Packing and Arranging

- [Plater](https://github.com/Rhoban/Plater) - 3D-printer parts placer and plate generator, written in C++
- [libnest2d](https://github.com/tamasmeszaros/libnest2d) - 2D irregular bin packaging and nesting library written in modern C++
- [nest2D](https://github.com/markfink/nest2D) - A 2D bin packaging tool for python
- [SVGnest](https://github.com/Jack000/SVGnest) - An open source vector nesting tool, written in JavaScript


## Hardware

### Printers

### Firmware

### CAD


