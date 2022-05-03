
# 🤖💌 Generative OpenSCAD Challenge

I'm going to post this project idea on a few sites like kaggle, huggingface, discord, etc. to see if others are keen to experiment collaboratively.  

I suspect a lot of the persons arriving to this repo may have never heard of OpenSCAD.

OpenSCAD is parametric design syntax, it is geometry as code.

Generative OpenSCAD would be an infinite library of 3d compositional objects & compositional vector art. 

OpenSCAD is "compositional" which means the objects are functions (monadic functors) with polymorphic argument-parameters.   Everybody starts learning OpenSCAD with a circle() & square() but that really misses the power. 

An example is a bolt() function from the BOSL2 openscad library which has idiomatic enumerated parameters that are intuitive called "size" which consists of names such as { "m3", "m4", "m5", "m6", ... }
/(KIND NOTE TO US READERS: those are commonly used METRIC bolt sizes!)/

The OpenSCAD object internally represents the correct length and simulate the thread pitch.  The key type parameter let's the bolt become DIN 965 (phillips) or DIN 912 (allen key) or defaults to something sensible.   All those complex 'measurements' such as thread pitch are *optional* parameters, with openscad I don't need to know the thread pitch to summon a bolt or import a poly-STL/OBJ representation of dots and kill my rendering performance. 

With OpenSCAD the high level idiomatic representation is better, especially with an LSP & intellisense in your editor.  I never need to lookup the mechanical thread pitch tables because they arecontained within the object or library so finally mech-designers can design parts as code and keep them in version control.  These libraries for bolts and rails are just like useful high-utility code libraries like dates & times that nearly every application uses!

OpenSCAD syntax is better for observational version control - not like OBJ's & STL's which are textfiles, but they are principally geometric points & poly-triangles that must be rendered and only look like the shape until you zoom in!  Whereas OpenSCAD objects are intuitively named functions that generate the vector shapes, curves, etc. in 3d ... not points and triangles in space with no context until they are rendered into an STL or OBJ. 

In OpenSCAD different object shapes can be joined or used as tools to subtract.  This approach for generating shapes is a sensible way to progressively roll up more complex subassemblies and *could* make simulation of these systems (such as robotics).

This is not like other AI challenges, because a single parameter may determine many aspects of the shape, and the agent would definitely need to learn how to combine & subtract shapes.  To make the resulting code more readable there might be a high cost to allowing more functions and that may encourage the agent to generate DRY code. 

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

