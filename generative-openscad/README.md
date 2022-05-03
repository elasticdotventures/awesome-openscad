
# 🤖💌 Generative OpenSCAD Challenge

I'm going to post this project idea on a few sites like kaggle, huggingface, eAI & other AI related discords, etc. to see if others are keen to experiment collaboratively.  

## OpenSCAD for noobs
[OpenSCAD](https://openscad.org/) is parametric design syntax, it is geometry as code.

Generative OpenSCAD will provide an infinite library of 3d compositional objects & compositional vector art that will power the web3 metaverse. 

OpenSCAD has multiple language support for Python, TypeScript, C++ or RUST, even Java, here are some examples of engines supporting OpenSCAD:
* [https://openjscad.xyz/]()
* [https://implicitcad.org/]()
* [https://openscad.org/downloads.html]()
* [https://cadhub.xyz]()
## Why OpenSCAD is awesome for Generative Artificial Intelligence

OpenSCAD syntax is "compositional" which means the objects are functions (monadic functors) with polymorphic argument-parameters. 

Everybody starts learning OpenSCAD with a circle() & square() but that really misses the power.  OpenSCAD objects are a powerful set of primitive tools for agents to create & utilize in simulators.   

OpenSCAD is a straightforward codex for an LM on paper, it can be learned quickly and may provide insight on how an LM is thinking.   There is more than one way to accomplish the same goal in parameteric design, so there will be new ways to quantiatively evaluate model performance. 
## Screw() & Libraries for OpenSCAD 

OpenSCAD libraries behave just like useful high-utility code libraries - but instead of fucntions for stuff like dates & times, they are 2d parametrically constrained shapes & 3d objects. 

A straightforward but powerful example is the [screw()](https://github.com/revarbat/BOSL2/wiki/screws.scad) function from the [BOSL2](https://github.com/revarbat/BOSL2/wiki) openscad library which has idiomatic enumerated parameters that are intuitively called "name" which consists of names such as { "M3", "M4", "M5", "M6", "#8-32" ... }  


The OpenSCAD object internally represents the correct length and calculates the thread pitch, drive_size, oversize, shank, tolerances, etc.  The "name" parameter can be used with the "head" to let the screw switch from DIN 965 (phillips) or DIN 912 (allen key), it's perfect & toil free. 

When I'm designing I'm racing the clock until I can start fabricating -- I never want to waste time yak-shaving finding or designing my own bolt when (as an engineer) I should be designing & testing the machine.  I don't need to specify *optional* parameter with openscad.  

The mechanical thread pitch tables in bolt are also built-in to the library.  The designer never needs to look them up! Also mechanical engineering parts & systems with OpenSCAD will instantly let teams use GIT version control (and build pipelines) awesome. 

## OpenSCAD compared to 3D formats such as STL/OBJ or Autodesk SketchUp

With OpenSCAD the high level idiomatic representation is intuitive, especially in an editor like VS-Code which has OpenSCAD LSP w/intellisense built-in.  Editing objects is simply naming the "name" attribute to something else.

OpenSCAD also don't need to import thousands of poly-STL/OBJ representation of dots & triangles.   To edit an STL or OBJ is painful because it requires moving what might sometimes be tens of thousands of geometrically constrained points & shapes. 

Whereas OpenSCAD objects are intuitively named functions that generate the vector shapes, curves, etc. in 3d ... not points and triangles in space with no context until they are rendered into an STL or OBJ. 

In OpenSCAD different object shapes can be joined (unioned) or used as tools to subtract.  This approach for generating shapes is a sensible way to progressively roll up more complex subassemblies and *could* make simulation of these systems (such as robotics, but any equivalent mechanical-engineering task).

## What will be hard about Generative OpenSCAD

Generative OpenSCAD is not like other AI challenges.  A single parameter may control many aspects of the shape, and the agents to be successful will definitely need to learn how to combine & subtract shapes.   To make the resulting OpenSCAD code more readable there might be a high cost to allowing more functions and a high value on generating concise DRY code. 


I can envision (someday, in the distant future) to have a simulation pipeline for the objects that provides a cognitive agent that can understand project requirements with the means to both generate & subsequently evaluate the performance of the object and then theorize a better design which it can submit to the simulation on the subsequent iteration. 

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
    

## Task B: Convert 3d STL or OBJ to equivalent OpenSCAD
    * it is probably to convert SVG to OpenSCAD (pretty easy)

## TASK C: show us something cool related to OpenSCAD & AI

