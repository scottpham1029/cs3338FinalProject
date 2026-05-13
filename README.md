HDR Imagery Dynamic Tone Mapping
OpenFX Plugin for Davinci Resolve
----------------------------------------
HDR tone mapping in DaVinci Resolve (especially when converting HDR to SDR) 
is best achieved using the Color Space Transform (CST) OFX, Project Color 
Management, or Node-based HDR wheels to map high-luminance highlights into 
the 100-nit SDR range while preserving details.


Project Objective
-----------------
The objective of HDR Imagery Dynamic Tone Mapping is to design and develop 
an OpenFX plugin for DaVinci Resolve that provides dynamic tone mapping 
for HDR footage. The plugin is intended to analyze image luminance, 
preserve highlight and shadow detail, and produce a visually balanced 
output for different display targets.

The project focuses on creating a structured video-processing workflow 
that allows editors to manage HDR content more efficiently. By integrating 
directly into DaVinci Resolve through the OpenFX plugin framework, 
the software aims to provide a practical tool that fits into an 
existing post-production pipeline.


Why This Project Is Needed
--------------------------
HDR footage contains a wider luminance and color range than many standard 
displays can accurately reproduce. Without proper tone mapping, important 
image details can be lost due to clipped highlights, crushed shadows, 
or inconsistent brightness across scenes.

This project addresses the need for a more efficient and consistent 
HDR correction workflow. Instead of relying entirely on manual color 
adjustments, the plugin provides automated tone mapping support 
while still allowing users to fine-tune the image based 
on creative or technical requirements.

Features
--------
The plugin will include dynamic tone mapping capabilities that adjust 
image brightness and contrast based on frame or scene luminance data. 
Core controls will include exposure adjustment, highlight roll-off, 
shadow recovery, contrast, saturation protection, and output 
display targeting.

Additional features will include selectable presets such as Natural, 
Cinematic, Broadcast Safe, and Custom. The plugin will also provide 
preview comparison modes, allowing users to compare the original 
HDR input against the processed output before applying 
changes to the final video.

Development Status
------------------
HDR IMagery Dynamic Tone Mapping is a prototype and is not publicly deployed. The
project focuses on design, planning, and conceptual implementation rather
than a finished consumer application. Features are demonstrated and tested
locally during development.


Accessing The Application
-------------------------
At this stage, the application is not available for public download. The prototype is 
intended to be run locally during development. Future versions tbd

Project Management
------------------
Project planning, task assignments and progressive tracking were managed using Jira

Jira Link: ---placeholder---


Team Members
------------
Alejandro Lopez
Brian Fuentes
Joshua Padilla
Ludwig Vincent
Scott Pham



