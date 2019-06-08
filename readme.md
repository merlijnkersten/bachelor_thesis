# About
This repository holds the code for my bachelor thesis project, conducted at the FOM AMOLF institute for complex matter in Spring 2018 while I studied at Amsterdam University College

The institute does research into real-life performance of various solar cells in Dutch climatic conditions. To this end, they have six different solar panels installed outside their offices, for which they meassure the output and various climatic conditions (see [https://www.lmpv.nl/solar-field/](the project's website "lmpv.nl/solar field"). 

My project focused on designing a tool that measures the diffuseness of incoming solar radiation, something that they could not yet measure but which is important especially to bi-facial solar panels. One way to measure this is by comparing the amount of incoming solar radiation in opposite directions (e.g. from straight up and straight down) and to then calculate a diffuseness metric. The more different directions you measure, the more accurate your measurement becomes. My objective was to find out what the optimum number of directions was (given building costs and complexity).

To find out, I wrote a Mathematica script that simulates a measurement tool with various number of sides. In the end, we settled on 12 sensors (6 different directions), and such a tool is currently being tested at AMOLF.

If you have any further questions, please do not hesitate to contact me. 
