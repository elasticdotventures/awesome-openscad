
# 🤖💌 Generative OpenSCAD Challenge

I'm going to post this project idea on a few sites like kaggle to see if others are keen to experiment collaboratively.  

The goals of Generative OpenSCAD are to accomplish 3d generative tasks, broadly described below.

OpenSCAD is parametric geometry as code.
Generative OpenSCAD would be an infinity library of 3d compositional objects & compositional vector art. 

The keyword about /why/ openSCAD is better, is that it is "compositional" which means the objects are functional with polymorphic parameteres.  An example is a bolt() function receiving an idiomatic enumerated parameter from the set: "m3, m4, m5, m6, ..." (these are commonly used metric bolt sizes for US readers).

the object internally represents the correct length and simulate the thread pitch.  These different shapes can be joined or used as tools to subtract.  This approach for generating shapes is a sensible way to progressively roll up more complex subassemblies and *could* make simulation of these systems (such as robotics).

I can envision (someday, in the distant future) to have a simulation pipeline for the objects that provides a cognitive agent with the means to evaluate the performance of the object and then theorize a better design which it can submit to the simulation.

## Pre-toil tasks
    * build a map/index of openscad code libraries on the Internet (this repo)
    * build tool to download & validate objects listed in the awesome-openscad repo.
    * render STL's & 2D views from 12 orientations (top, bottom, 4 sides)
    * create (introspectively transpile?) compositional test harnesses for openscad objects from lib for use in learning.
    * OPTIONAL: thingiverse, grabcad, kicad, any other parts libraries with STL's for more objects

## Task A: "LM" Language Model /text description/ to OpenSCAD syntax
My proposed approach:
    * use instructional GPT-Instruct similar compositional approach like DALLE-2 or CLIP, but with open image models
    * create an LM codex that can output valid openscad code (using the pre-toil above)
    * render openscad code into STL's (using the pre-toil above)
    * use has valid parameters/code syntax of codex in reinforcement
    
    * STRETCH GOAL: adjustable componentization & naming conventions. 
    it is most useful to output an intuitive compositional syntax for writing sensible code (i.e. naming conventions for objects with polymorphic parameters that make sense, so a propellor is named a 'propellor')  🤔: how to measure?
    

## Task B: Convert 3d STL to equivalent OpenSCAD
    * it is probably to convert SVG to OpenSCAD (pretty easy)

## TASK C: show us something cool related to OpenSCAD & AI

