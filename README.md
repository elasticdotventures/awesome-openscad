[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub Stars](https://img.shields.io/github/stars/elasticdotventures/awesome-openscad?style=social)](https://github.com/elasticdotventures/awesome-openscad)
[![Project Status: WIP](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)

## 🎯 Goal

Bring more awesomeness and harmony to the OpenSCAD community by curating the best tools, libraries, and resources.

Contributions welcome! If you maintain an OpenSCAD or related project, please open a PR.

## Awesome Communities

- **OpenSCAD GitHub**: The [official source](https://github.com/openscad/openscad) of OpenSCAD.
- **IRC & Matrix**: Real‑time chat on Libera.Chat (#openscad)<br/>[![Visit our IRC channel](https://kiwiirc.com/buttons/irc.libera.chat/openscad.png)](https://kiwiirc.com/client/irc.libera.chat/#openscad)
- **Reddit**: [r/OpenSCAD](https://reddit.com/r/openscad).
- **Mastodon**: Tag posts with [#OpenSCAD](https://mastodon.social/web/tags/openscad).

## PartCad

A modular design platform supporting OpenSCAD, CadQuery, and Build123d via YAML assemblies.  
Includes VS Code integration, OCP Viewer, AI‑assisted model generation, and exports to SVG, PNG, STEP, BREP, STL, 3MF, ThreeJS, and OBJ. If you're wondering how to take OpenSCAD to the next level please show PartCad your love! Start designing modular hardware! PartCAD is the standard for documenting manufacturable physical products. 🤯
[partcad.org](https://partcad.org) | [github.com/partcad](https://github.com/partcad)

## Friends of SCAD

- 🦀 **CSGRS**: [timschmidt/csgrs](https://github.com/timschmidt/csgrs/) — BSP‑based constructive solid geometry in Rust.
- ⚙️ **Fornjot**: [hannobraun/fornjot](https://github.com/hannobraun/fornjot) — Boundary‑representation CAD in Rust.
- 🐍 **CadQuery**: [cadquery/cadquery](https://github.com/cadquery/cadquery) — Python DSL for parametric CAD.
- 🧰 **Build123d**: [gumyr/build123d](https://github.com/gumyr/build123d) — Python BRep library on OpenCascade with context‑manager API for parametric modeling.
- 🧱 **OpenCascade**: [OpenCascade/OpenCascade](https://github.com/Open-Cascade-SAS/OCCT) — C++ CAD kernel and modeling toolkit.
- 📐 **ImplicitCAD**: [Haskell-Things/ImplicitCAD](https://github.com/Haskell-Things/ImplicitCAD) — Haskell‑based parametric CAD (compatibility uncertain).

## Language Bindings

Compositional transpilation and visualization libraries for OpenSCAD.

### 🦀 Rust

- **Rust‑Scad**
  - **Repo:** [TheZoq2/Rust-Scad](https://github.com/TheZoq2/Rust-Scad)
  - ![Last commit](https://img.shields.io/github/last-commit/TheZoq2/Rust-Scad)
  - **Description:** DSL for generating OpenSCAD models using Rust’s type safety and cargo workflow.

### 🌐 WebAssembly

- **openscad-wasm**
  - **Repo:** [openscad/openscad-wasm](https://github.com/openscad/openscad-wasm)
  - ![Last commit](https://img.shields.io/github/last-commit/openscad/openscad-wasm)
  - **Description:** Official WebAssembly port of the OpenSCAD core, enabling in‑browser rendering and editing.

### 🐍 Python

- **OpenPySCAD**

  - **Repo:** [taxpon/openpyscad](https://github.com/taxpon/openpyscad)
  - ![Last commit](https://img.shields.io/github/last-commit/taxpon/openpyscad)
  - **Description:** Lightweight Python wrapper for programmatic SCAD script generation.

- **python-threaded-openscad**
  - **Repo:** [mrkoz/python-threaded-openscad](https://github.com/mrkoz/python-threaded-openscad)
  - ![Last commit](https://img.shields.io/github/last-commit/mrkoz/python-threaded-openscad)
  - **Description:** Adds multithreading and non‑blocking OpenSCAD calls to Python workflows.

#### Notable Python Projects

- **pyDactyl**

  - **Repo:** [karosc/pyDactyl](https://github.com/karosc/pyDactyl)
  - ![Last commit](https://img.shields.io/github/last-commit/karosc/pyDactyl)
  - **Description:** Interactive web‑based OpenSCAD editor built atop Python.

- **pyKeeb**
  - **Repo:** [r4dr3fr4d/pykeeb](https://github.com/r4dr3fr4d/pykeeb)
  - ![Last commit](https://img.shields.io/github/last-commit/r4dr3fr4d/pykeeb)
  - **Description:** Parametric keyboard layout generator combining Python and SCAD.

### 🦄 TypeScript

- **scad-js**

  - **Repo:** [scad-js/scad-js](https://github.com/scad-js/scad-js)
  - ![Last commit](https://img.shields.io/github/last-commit/scad-js/scad-js)
  - **Description:** Fluent TypeScript API for building SCAD models.

- **openscad-format**

  - **Repo:** [Maxattax97/openscad-format](https://github.com/Maxattax97/openscad-format)
  - ![Last commit](https://img.shields.io/github/last-commit/Maxattax97/openscad-format)
  - **Description:** Node.js‑based formatter for `.scad` files.

- **NodeSCAD**
  - **Repo:** [ad-si/nodescad](https://github.com/ad-si/nodescad)
  - ![Last commit](https://img.shields.io/github/last-commit/ad-si/nodescad)
  - **Description:** Node.js wrapper for invoking OpenSCAD from JavaScript scripts.

## Platforms Supporting OpenSCAD Syntax

- **_OpenSCAD_**

  - _The source of truth for everybody else._
  - **Environment:** Desktop (Windows, Linux, macOS)
  - **Syntax & Workflow:** Native script-based (`.scad`)
  - **Key Features:** Parametric CSG engine, live preview & render, import/export STL, DXF, SVG, OFF, AMF
  - **Status:** Active
  - **Link:** [GitHub](https://github.com/openscad/openscad)
  - **Last commit:** ![Last commit](https://img.shields.io/github/last-commit/openscad/openscad)
  - **Latest release:** ![Release](https://img.shields.io/github/v/release/openscad/openscad)

- **OpenSCAD Studio**

  - _A modern OpenSCAD editor for makers, with live preview, diagnostics, and AI-assisted iteration._
  - **Environment:** Web app and macOS desktop app
  - **Syntax & Workflow:** Native OpenSCAD (`.scad`) editing with browser WebAssembly rendering and desktop native OpenSCAD rendering
  - **Key Features:** Monaco-based editor, live 3D and SVG preview, customizer controls, multi-file desktop projects, measurement tools, share links, and AI copilot support for hosted or local models
  - **Status:** Active
  - **Link:** [openscad-studio.pages.dev](https://openscad-studio.pages.dev) / [GitHub](https://github.com/zacharyfmarion/openscad-studio)
  - **Last commit:** ![Last commit](https://img.shields.io/github/last-commit/zacharyfmarion/openscad-studio)
  - **Latest release:** ![Release](https://img.shields.io/github/v/release/zacharyfmarion/openscad-studio)

- **FreeCAD (OpenSCAD Workbench)**

  - _A venerable free open-source tool featuring an OpenSCAD workbench._
  - **Environment:** Desktop (Windows, Linux, macOS)
  - **Syntax & Workflow:** Workbench plugin for `.scad`
  - **Key Features:** Import SCAD scripts, hybrid CSG & FEM via Calculix
  - **Status:** Active
  - **Link:** [GitHub](https://github.com/FreeCAD/FreeCAD)
  - **Last commit:** ![Last commit](https://img.shields.io/github/last-commit/FreeCAD/FreeCAD)
  - **Latest release:** ![Release](https://img.shields.io/github/v/release/FreeCAD/FreeCAD)

- **JSCAD (OpenJSCAD.org)**

  - _Previously known as OpenJSCAD, online self-hostable web-based UI and CLI._
  - **Environment:** Web & CLI (Node.js/browser)
  - **Syntax & Workflow:** JavaScript-based scripting
  - **Key Features:** Browser & CLI tools, parametric 2D/3D in JS, multi-format export (STL, DXF, SVG)
  - **Status:** Active
  - **Link:** [GitHub](https://github.com/jscad/OpenJSCAD.org)
  - **Last commit:** ![Last commit](https://img.shields.io/github/last-commit/jscad/OpenJSCAD.org)

- **CadHub**

  - **Environment:** Web-based IDE
  - **Syntax & Workflow:** Live OpenSCAD editor in browser
  - **Key Features:** Integrated IDE, live preview, console, parameter customizer
  - **Status:** Beta
  - **Link:** [cadhub.xyz](https://cadhub.xyz) / [GitHub](https://github.com/Irev-Dev/cadhub)
  - **Last commit:** ![Last commit](https://img.shields.io/github/last-commit/Irev-Dev/cadhub)

- **Blender‑openSCAD**

  - **Environment:** Blender plugin
  - **Syntax & Workflow:** Embed OpenSCAD in Blender via WASM/Rust
  - **Key Features:** Shared engine integration, cargo installer
  - **Status:** Preview
  - **Link:** [GitHub](https://github.com/elasticdotventures/blender-openSCAD)
  - **Last commit:** ![Last commit](https://img.shields.io/github/last-commit/elasticdotventures/blender-openSCAD)

- **RapCAD**

  - **Environment:** Desktop (C++/Qt)
  - **Syntax & Workflow:** OpenSCAD‑compatible IDE
  - **Key Features:** MPFR/GMP arbitrary precision, multithreading, CGAL backend, dynamic arrays
  - **Status:** Maintained
  - **Link:** [GitHub](https://github.com/GilesBathgate/RapCAD)
  - **Last commit:** ![Last commit](https://img.shields.io/github/last-commit/GilesBathgate/RapCAD)
  - **Latest release:** ![Release](https://img.shields.io/github/v/release/GilesBathgate/RapCAD)

- **Libre3D (`render-3d`)**

  - **Environment:** PHP library (server-side)
  - **Syntax & Workflow:** PHP wrapper that invokes OpenSCAD and POV‑Ray via Composer allowing you to load SCAD/STL/OBJ, convert to POV format, then render to PNG/SVG.
  - **Key Features:** Composer-installed (~1.2.0) PHP wrapper with autoload support; configurable working directory, executable paths, image dimensions, and buffer modes; automatic STL→POV conversion and rendering using a dynamic grid scene, with optional buffered or direct output.
  - **Status:** Maintained
  - **Link:** [GitHub](https://github.com/libre3d/render-3d)
  - **Last commit:** ![Last commit](https://img.shields.io/github/last-commit/libre3d/render-3d)
  - **Latest release:** ![Release](https://img.shields.io/github/v/release/libre3d/render-3d)

- **OpenSCAD.cloud**

  - **Environment:** Web-based (Browser)
  - **Syntax & Workflow:** WASM port of OpenSCAD
  - **Key Features:** Live editing, multi‑file support, shareable links, STL export
  - **Status:** Beta
  - **Link:** [openscad.cloud](https://openscad.cloud/) / [GitHub](https://github.com/Autodrop3d/openscad.cloud)
  - **Last commit:** ![Last commit](https://img.shields.io/github/last-commit/Autodrop3d/openscad.cloud)

- **ZenCad**

  - **Environment:** Desktop (Python + Qt)
  - **Syntax & Workflow:** OpenSCAD‑style scripting in Python, backed by the OpenCASCADE kernel
  - **Key Features:** Interactive REPL & GUI, Jupyter support, advanced B‑Rep ops (sweeps, lofts), mesh analysis, standalone or embeddable in Python scripts
  - **Status:** Active
  - **Link:** [GitHub](https://github.com/mirmik/zencad) | [Docs](https://mirmik.github.io/zencad/en/index.html)
  - **Last commit:** ![Last commit](https://img.shields.io/github/last-commit/mirmik/zencad)

- **BlocksCAD**

  - **Environment:** Web-based (Blockly)
  - **Syntax & Workflow:** Block-based OpenSCAD with code view toggle
  - **Key Features:** Drag‑and‑drop, XML/SCAD export
  - **Status:** Active
  - **Link:** [blockscad3d.com](https://www.blockscad3d.com/)

- **Models @ MakeWithTech**

  - **Environment:** Web-based customizer
  - **Syntax & Workflow:** Forms-based parameter input
  - **Key Features:** Thingiverse search, UI forms, high‑capacity rendering
  - **Status:** Active
  - **Link:** [models.makewithtech.com](https://models.makewithtech.com/)

## Editor & IDE Extensions

- **VS Code (OpenSCAD Language Support)**

  - **Environment:** Desktop IDE
  - **Syntax & Workflow:** LSP-based support for `.scad`
  - **Key Features:** Formatter (Topiary), auto‑completion, jump to definition, hover docs, symbols, error diagnostics, preview & cheatsheet
  - **Status:** Active
  - **Link:** [GitHub - openscad-LSP](https://github.com/Leathong/openscad-LSP), [Marketplace](https://marketplace.visualstudio.com/items?itemName=Leathong.openscad-language-support) / [GitHub - openscad-support-vscode](https://github.com/Leathong/openscad-support-vscode)
  - **Last commit (VSC support):** ![Last commit](https://img.shields.io/github/last-commit/Leathong/openscad-support-vscode)
  - **Last commit (LSP):** ![Last commit](https://img.shields.io/github/last-commit/Leathong/openscad-LSP)
  - **Latest release (LSP):** ![Release](https://img.shields.io/github/v/release/Leathong/openscad-LSP?include_prereleases)

- **VS Code (Antyos OpenSCAD Extension)**

  - **Environment:** Desktop IDE
  - **Syntax & Workflow:** VS Code extension using TextMate grammar and command palette integration for `.scad` files
  - **Key Features:**
    - Syntax highlighting for built‑in and user modules
    - Customizer syntax support (drop‑downs, sliders, tabs)
    - Preview in OpenSCAD & Export Model buttons
    - Code snippets for common patterns
    - Built‑in OpenSCAD cheatsheet
  - **Status:** Active (37K+ installs)
  - **Link:** [Marketplace](https://marketplace.visualstudio.com/items?itemName=Antyos.openscad) / [GitHub](https://github.com/Antyos/vscode-openscad)
  - **Last commit:** ![Last commit](https://img.shields.io/github/last-commit/Antyos/vscode-openscad)
  - **Latest release (LSP):** ![Release](https://img.shields.io/github/v/release/Antyos/vscode-openscad?include_prereleases)

- **Code Editors** (Netbeans, Vim, Emacs, Atom)

  - **Environment:** Local editors
  - **Syntax & Workflow:** Syntax highlighting & LSP
  - **Key Features:** Language Server Protocol support, diagnostics (varies by editor)
  - **Status:** Experimental
  - **Link:** [LSP GitHub PR](https://github.com/openscad/openscad/pull/3635)

## Core Libraries

- **2D Connection Library**

  - [YouMagine](https://www.youmagine.com/designs/openscad-2d-connection-library)
  - **Description:** A set of OpenSCAD modules for creating 2D interlocking tabs and slots, ideal for laser‑cut assemblies (e.g., tripods, handles, camera mounts).

- **Celtic Knots**

  - [beanz/celtic-knot-scad](https://github.com/beanz/celtic-knot-scad)
  - ![Last commit](https://img.shields.io/github/last-commit/beanz/celtic-knot-scad)
  - **Description:** Parametric generator for intricate interlaced Celtic knot patterns, configurable by curve resolution, strand count, and line thickness.

- **MCAD: Parametric CAD Library**

  - [openscad/MCAD](https://github.com/openscad/MCAD)
  - ![Last commit](https://img.shields.io/github/last-commit/openscad/MCAD)
  - **Description:** General-purpose library of mechanical primitives including gears, springs, bearings, fasteners, and structural profiles. Released under CC0 for open reuse.

- **Shapes**

  - [Thingiverse](https://www.thingiverse.com/thing:212041)
  - **Description:** Collection of basic parametric shape primitives (boxes, cylinders, spheres) and helper modules for rapid prototyping in OpenSCAD.

- **U‑Joint Library**

  - [Thingiverse](https://www.thingiverse.com/thing:125939)
  - **Description:** Parametric modules for designing universal joints, allowing adjustment of shaft diameters, flange dimensions, and cross‑section geometry.

- **SCAD Utils**

  - [OskarLinde/scad-utils](https://github.com/OskarLinde/scad-utils)
  - ![Last commit](https://img.shields.io/github/last-commit/OskarLinde/scad-utils)
  - **Description:** A toolkit of functions for boolean operations, morphological transformations, array manipulation, and utility math aiming to extend OpenSCAD’s core capabilities.

- **FunctionalOpenSCAD**

  - **Repo:** [thehans/FunctionalOpenSCAD](https://github.com/thehans/FunctionalOpenSCAD)
  - ![Last commit](https://img.shields.io/github/last-commit/thehans/FunctionalOpenSCAD)
  - **Description:** Re‑implements OpenSCAD’s built‑in modules as pure functions operating on mesh data (`poly`), exposing vertex, path, and face geometry for advanced shape analysis, custom transformations, and algorithmic modeling entirely within user scripts.

- **funcutils**

  - **Repo:** [thehans/funcutils](https://github.com/thehans/funcutils)
  - ![Last commit](https://img.shields.io/github/last-commit/thehans/funcutils)
  - **Description:** A collection of functional programming utilities for OpenSCAD modeled after C++ STL algorithms, providing higher‑order functions (map, filter, fold), list manipulation, math, string, and type‑checking operations via function‑literals to create expressive, reusable modules.

- **dotSCAD**

  - **Repo:** [JustinSDK/dotSCAD](https://github.com/JustinSDK/dotSCAD)
  - ![Last commit](https://img.shields.io/github/last-commit/JustinSDK/dotSCAD)
  - **Description:** Vast collection of math‑ and geometry‑focused modulessuch as arcs, spirals, Béziers, splines, hulls, lofts, sweeps, and path/region operations.

- **BOSL2**

  - **Repo:** [BelfrySCAD/BOSL2](https://github.com/BelfrySCAD/BOSL2)
  - ![Last commit](https://img.shields.io/github/last-commit/BelfrySCAD/BOSL2)
  - **Description:** An “everything” library of shapes, masks, math routines, attachment‑based positioning, rounding/filleting, texture embossing, VNF/polygon operations, shorthands, and a parts library (gears, threads, hinges, etc.) to simplify advanced OpenSCAD modeling.

- **agentscad**

  - **Repo:** [GillesBouissac/agentscad](https://github.com/GillesBouissac/agentscad)
  - ![Last commit](https://img.shields.io/github/last-commit/GillesBouissac/agentscad)
  - **Description:** Utilities for parametric modeling: canvas & lithophane generators, snap‑joint and Hirth joint modules, detailed threaded‑screw implementations (metric, UNC/UNF, BSW/BSF), beveling, glue‑shape locators, and PCB/box shell templates.

- **OpenSCADutil**

  - **Repo:** [franpoli/OpenSCADutil](https://github.com/franpoli/OpenSCADutil)
  - ![Last commit](https://img.shields.io/github/last-commit/franpoli/OpenSCADutil)
  - **Description:** Curated collection of accessory and utility modules: IKEA Skådis pegboard accessories, knurled knobs, soldering‑sponge templates, AirTag cases, and other workflow‑focused scripts for rapid OpenSCAD prototyping.

- **NopSCADlib**

  - **Repo:** [nophead/NopSCADlib](https://github.com/nophead/NopSCADlib)
  - ![Last commit](https://img.shields.io/github/last-commit/nophead/NopSCADlib)
  - **Description:** Comprehensive parts and utility framework: motor mounts, electronic housings, chamfers, fillets, precision holes, BOM & DXF generators, automated documentation and exploded‑view assembly scripts for complex OpenSCAD projects.

- **BH-Lib**

  - **Repo:** [brandonhill/BH-Lib](https://github.com/brandonhill/BH-Lib)
  - ![Last commit](https://img.shields.io/github/last-commit/brandonhill/BH-Lib)
  - **Description:** Comprehensive collection of OpenSCAD helper functions and modules including geometry transforms (clamp, offset, chamfer), 2D/3D primitives (rounded_cube, torus, capsule), and parametric hardware components (gears, beams, fasteners).

- **Orientation Models**

  - **Repo:** [tanius/openscad-models](https://github.com/tanius/openscad-models)
  - ![Last commit](https://img.shields.io/github/last-commit/tanius/openscad-models)
  - **Description:** Personal archive of fully parametric OpenSCAD experiments and designs, ranging from mechanical parts to decorative patterns, illustrating real-world code-driven CAD workflows and advanced shape generation techniques.

- **OMDL (Mechanical Design Library)**

  - **Repo:** [royasutton/omdl](https://github.com/royasutton/omdl)
  - ![Last commit](https://img.shields.io/github/last-commit/royasutton/omdl)
  - **Description:** Documented mechanical toolkit offering beams, brackets, fasteners, polyhedron utilities, and test suites; includes a setup script for library installation and an automated API site (v0.6), all under LGPL for open-hardware projects.

- **openSCAD_functions**

  - **Repo:** [dinther/openSCAD_functions](https://github.com/dinther/openSCAD_functions)
  - ![Last commit](https://img.shields.io/github/last-commit/dinther/openSCAD_functions)
  - **Description:** Modular library of standalone, well-documented functions covering tasks like chamfers, coordinate conversions, mesh processing, and Boolean utilities, optimized for minimal dependencies. Each is self-contained within it's respective directory along with demo scripts.

- **openscad-fiddlybits**

  - **Repo:** [mathcodeprint/openscad-fiddlybits](https://github.com/mathcodeprint/openscad-fiddlybits)
  - ![Last commit](https://img.shields.io/github/last-commit/mathcodeprint/openscad-fiddlybits)
  - **Description:** Lightweight toolkit of focused SCAD scripts aimed at streamlining common modeling chores. Provides dimension arrows, explode-view helpers, object-array generators, and parametric bearing models.

- **Lofting**

  - **Repo:** [jakubczaplicki/this-to-that](https://github.com/jakubczaplicki/this-to-that)
  - ![Last commit](https://img.shields.io/github/last-commit/jakubczaplicki/this-to-that)
  - **Description:** Implements profile lofting in pure OpenSCAD by interpolating between two or more 2D cross-sections to create smooth, organic 3D shapes. Includes usage examples, parameter controls for interpolation steps, and support for multi-profile transitions.

- **JOSL Rack**

  - **Repo:** [jernst/josl](https://github.com/jernst/josl) ![Last commit](https://img.shields.io/github/last-commit/jernst/josl)
  - **Description:** A general-purpose OpenSCAD library by Johannes (“JOSL”) that organizes reusable modules for splitting oversized models with various joint types, generating Bezier paths, and rendering 7×5‑pixel text for etching or engraving. Set up via your `OPENSCADPATH` to include example scripts and demos.

## Tutorials & Workflows

- **Naminukas Workflow**

  - **Repo:** [kikaitachi/naminukas](https://github.com/kikaitachi/naminukas)
  - ![Last commit](https://img.shields.io/github/last-commit/kikaitachi/naminukas)
  - **Description:** A reference parametric design pipeline showcasing best practices: JSON‑driven parameter files, modular SCAD includes, Makefile automation for batch renders, and variant generation. Ideal for structuring scalable OpenSCAD projects and automated output workflows.

- **OpenSCADObjects**

  - **Repo:** [jeffbarr/OpenSCADObjects](https://github.com/jeffbarr/OpenSCADObjects)
  - ![Last commit](https://img.shields.io/github/last-commit/jeffbarr/OpenSCADObjects)
  - **Description:** A curated collection of over 75 handcrafted parametric, customizer‑enabled objects designed for easy adaptation and rapid FDM printing. Features various geometric tessellations, functional parts, and decor models.

- **Cookie Cutters**

  - **Repo:** [benjaminwand/cookie-cutters](https://github.com/benjaminwand/cookie-cutters)
  - ![Last commit](https://img.shields.io/github/last-commit/benjaminwand/cookie-cutters)
  - **Description:** A collection of example OpenSCAD scripts generating a variety of cookie cutter shapes (e.g., geometric bases, novelty forms like rockets and viruses). Demonstrates Bézier-curve-based outline modeling and provides tutorial links for learning curve mathematics.

## Data Exchange & Automation

### Import Tools

- **svg2dxf**

  - **Repo:** [Zigazou/svg2dxf](https://github.com/Zigazou/svg2dxf) ![Last commit](https://img.shields.io/github/last-commit/Zigazou/svg2dxf)
  - **Description:** Bash script using Inkscape and pstoedit to convert SVG files into DXF format, enabling crisp 2D vector imports for extrusion and boolean operations in OpenSCAD.

- **SVG2SCAD**

  - **Repo:** [Spiritdude/SVG2SCAD](https://github.com/Spiritdude/SVG2SCAD) ![Last commit](https://img.shields.io/github/last-commit/Spiritdude/SVG2SCAD)
  - **Description:** Perl utility that parses SVG path data and outputs OpenSCAD `polygon()` definitions, preserving Bézier curves and facilitating both linear and rotational extrusions.

- **fzz2scad**

  - **Repo:** [htho/fzz2scad](https://github.com/htho/fzz2scad) ![Last commit](https://img.shields.io/github/last-commit/htho/fzz2scad)
  - **Description:** Python tool that reads Fritzing `.fzz` circuit files and generates parametric SCAD modules for PCB outlines and front panels, streamlining custom enclosure creation.

- **Litho Research**

  - **Repo:** [Harakan/litho_research](https://github.com/Harakan/litho_research) ![Last commit](https://img.shields.io/github/last-commit/Harakan/litho_research)
  - **Description:** Experimental toolkit for automating raster‑to‑3D workflows: converts JPEG/PNG/BMP inputs into lithophane or relief STL models using custom SCAD modules (`lithopane`, `fromscad`) along with Potrace and triangulation tools. Includes example scripts and git submodule integration.

### EDA Imports

- **KiCad Libraries**

  - **Repo:** [mplewis/kicad-libraries](https://github.com/mplewis/kicad-libraries) ![Last commit](https://img.shields.io/github/last-commit/mplewis/kicad-libraries)
  - **Description:** Parametric OpenSCAD modules for common PCB footprints (SMD, through-hole, connectors) that match KiCad designs, simplifying integration of electronics into 3D-printed cases.

- **GerbToSCAD**
  - **Repo:** [drujensen/GerbToSCAD](https://github.com/drujensen/GerbToSCAD) ![Last commit](https://img.shields.io/github/last-commit/drujensen/GerbToSCAD)
  - **Description:** Parses Gerber PCB files to generate 3D SCAD models of copper layers and board outlines, enabling rapid prototyping of board housings and mechanical fixtures.

### Export Tools

- **Image Generator**

  - **Repo:** [openscad/image-generator](https://github.com/openscad/image-generator) ![Last commit](https://img.shields.io/github/last-commit/openscad/image-generator)
  - **Description:** Node.js service that renders SCAD scripts to PNG or SVG via a headless OpenSCAD process, ideal for automated thumbnail creation and documentation galleries.

- **OpenSCAD Batch Export**
  - **Repo:** [CameronBrooks11/OpenSCAD-Batch-Export](https://github.com/CameronBrooks11/OpenSCAD-Batch-Export) ![Last commit](https://img.shields.io/github/last-commit/CameronBrooks11/OpenSCAD-Batch-Export) ![Release](https://img.shields.io/github/v/release/CameronBrooks11/OpenSCAD-Batch-Export?include_prereleases)
  - **Description:** CLI and GUI tool for batch-exporting multiple STL files from a single SCAD model using CSV or JSON parameter files.

### Automation Utilities

- **openscad-amu**

  - **Repo:** [royasutton/openscad-amu](https://github.com/royasutton/openscad-amu) ![Last commit](https://img.shields.io/github/last-commit/royasutton/openscad-amu)
  - **Description:** Makefile-based automake utilities for scaffolding SCAD projects, resolving library dependencies, generating documentation, and packaging reusable component libraries.

- **scadlib**

  - **Repo:** [htho/scadlib](https://github.com/htho/scadlib)
  - ![Last commit](https://img.shields.io/github/last-commit/htho/scadlib)
  - **Description:** CLI toolkit for creating, scaffolding, and documenting OpenSCAD libraries. Includes `scadtool.py` for project management and `SCADDOC` spec for inline module/function annotations.

## 3D Printing Utilities

- **Print3r**

  - **Repo:** [Spiritdude/Print3r](https://github.com/Spiritdude/Print3r)
  - ![Last commit](https://img.shields.io/github/last-commit/Spiritdude/Print3r)
  - **Description:** A versatile CLI tool for slicing and printing 3D models (`.scad`, `.stl`, `.obj`, `.3mf`, etc.) across multiple slicers (Slic3r, PrusaSlicer, CuraEngine, SuperSlicer) with built‑in support for scaling, rotating, translating, random placement, auto‑centering, batch multiplication of parts, slicer‑independent settings (temperature, layer height, infill density, perimeters), interactive Gcode console, and PNG preview generation

- **Anti‑warp Walls**
  - **Repo:** [JohnStrunk/WhateverSCAD](https://github.com/JohnStrunk/WhateverSCAD)
  - ![Last commit](https://img.shields.io/github/last-commit/JohnStrunk/WhateverSCAD)
  - **Description:** Parametric OpenSCAD modules (`WWall`, `SWall`) that generate wave‑ or zig‑zag‑patterned walls to introduce relief areas and mitigate shrinkage‑induced warping in ABS prints, with optional solid framing for seamless integration into larger designs

## Assemblies & Multi‑Part

- **Constructive**

  - **Repo:** [solidboredom/constructive](https://github.com/solidboredom/constructive)
  - ![Last commit](https://img.shields.io/github/last-commit/solidboredom/constructive)
  - **Description:** Introduces a “stamping” DSL on top of OpenSCAD to concisely create interlocking mechanical parts (boxes, tubes, strips) and assemblies without heavy use of `difference()` or loops, focusing on assembly-oriented syntax for rapid prototyping.

- **Machine Design Framework**

  - **Repo:** [Axford/OpenSCADMachineDesignFramework](https://github.com/Axford/OpenSCADMachineDesignFramework)
  - ![Last commit](https://img.shields.io/github/last-commit/Axford/OpenSCADMachineDesignFramework)
  - **Description:** A reusable project template and module library for complex machine designs (CNC, robotics), providing standardized folder structure, dependency loading, kinematic helpers, and animation utilities to streamline large-scale OpenSCAD projects.

- **MoCad**

  - **Repo:** [davidthings/mocad](https://github.com/davidthings/mocad)
  - ![Last commit](https://img.shields.io/github/last-commit/davidthings/mocad)
  - **Description:** Offers a high‑level parts library where each part includes “Positions” (points + orientations) for easy connection and assembly; includes modules for common mechanical components and helper functions for position manipulation and coordinate maths.

## Electrical & Electronics

- **Electro‑Mech Components**

  - **Repo:** [htho/scadlib-electronic-components](https://github.com/htho/scadlib-electronic-components)
  - ![Last commit](https://img.shields.io/github/last-commit/htho/scadlib-electronic-components)
  - **Description:** Supplement to the `scadlib` toolkit providing parametric modules for electronic parts such as resistors, capacitors, headers, and sensors with mounting holes and footprint templates for rapid PCB-integrated design.

- **Coax Trap Form**

  - **Repo:** [SmittyHalibut/coax-trap-form](https://github.com/SmittyHalibut/coax-trap-form)
  - ![Last commit](https://img.shields.io/github/last-commit/SmittyHalibut/coax-trap-form)
  - **Description:** Parametric OpenSCAD model for designing coaxial trap coil forms used in multi‑band HF wire antennas. Users can adjust coil form diameter, number of turns, coaxial cable diameter, bolt hole size, and form thickness to generate STL-ready trap bodies. Includes example presets for 7.2 MHz (40/80 m) and 14.15 MHz (20 m) traps based on ARRL Antenna Handbook specifications.

- **Horizontal Server Rack**

  - **Repo:** [cromo/horizontal-rack](https://github.com/cromo/horizontal-rack) ![Last commit](https://img.shields.io/github/last-commit/cromo/horizontal-rack)
  - **Description:** Parametric OpenSCAD design for a compact horizontal (hanging) server rack. Configure rack width, depth, mounting hole positions, and clearance for server rails, then render 2D layouts or 3D preview.

- **KiCad Libraries**
  - **Repo:** [willdurand/kicad-libs](https://github.com/willdurand/kicad-libs) ![Last commit](https://img.shields.io/github/last-commit/willdurand/kicad-libs)
  - **Description:** William Durand’s collection of KiCad schematic symbols, PCB footprints, and corresponding 3D shapes (STEP) generated via OpenSCAD and converted in FreeCAD. Includes connectors (e.g., GameBoy slot), crystal oscillator packages, and utilities for seamless Eeschema/Pcbnew integration.

## Robotics CAD

- **mushr_cad**

  - **Repo:** [prl-mushr/mushr_cad](https://github.com/prl-mushr/mushr_cad)
  - ![Last commit](https://img.shields.io/github/last-commit/prl-mushr/mushr_cad)
  - **Description:** Full parametric OpenSCAD CAD library for the MuSHR robotic racecar platform. Includes design files for chassis, bumper, electronics mounts, and multiple versions (v2, v3), plus STL output directories for 3D printing. Blender scenes are provided to assemble and colorize parts.

- **lablock**
  - **Repo:** [fablab-nea/lablock](https://github.com/fablab-nea/lablock)
  - ![Last commit](https://img.shields.io/github/last-commit/fablab-nea/lablock)
  - **Description:** Parametric door‑locking mechanism for FabLabs and hackerspaces. Generates mounting plates, latch bodies, and actuator interfaces that fit standard knob‑cylinder locks, with customizable dimensions for different door thicknesses and handle sizes.

## Mechanical Components

### Threads

- **ThreadLib**

  - **Repo:** [adrianschlatter/threadlib](https://github.com/adrianschlatter/threadlib)
  - ![Last commit](https://img.shields.io/github/last-commit/adrianschlatter/threadlib)
  - **Description:** Comprehensive library of standard threads (metric, imperial, BSP, PCO, RMS) with built-in spec tables, lead-in/out tapers, and configurable resolutions for easy creation of bolts, nuts, and taps without manual dimension lookup.

- **Cap Generator**

  - **Repo:** [muesli/cap-generator](https://github.com/muesli/cap-generator)
  - ![Last commit](https://img.shields.io/github/last-commit/muesli/cap-generator)
  - **Description:** Parametric OpenSCAD module for thumb-cap generation: customize cap height, diameter, knurl pattern, and thread profile; designed for 3D printing PETG/PLA with ready-to-print examples and printing tips.

- **Metric Threads**

  - **Repo:** [gabfv/scad-metric-thread-library](https://github.com/gabfv/scad-metric-thread-library)
  - ![Last commit](https://img.shields.io/github/last-commit/gabfv/scad-metric-thread-library)
  - **Description:** Remix of an ISO metric thread library offering functions to create bolts, nuts, threaded holes, and insert-style screws; tweaked for Cura compatibility and real-world steel hardware dimensions.

- **Threads**

  - [dkprojects.net/openscad-threads](http://dkprojects.net/openscad-threads)
  - **Description:** Utilities for modeling metric and imperial screw threads with customizable pitch, major/minor diameters, and thread profiles.

### Screws, Nuts & Bolts

- **nutsnbolts**

  - **Repo:** [JohK/nutsnbolts](https://github.com/JohK/nutsnbolts)
  - ![Last commit](https://img.shields.io/github/last-commit/JohK/nutsnbolts)
  - **Description:** ISO metric fastener generator: `screw("MxL")`, `nut()`, `hole_through()`, `nutcatch_parallel()/nutcatch_sidecut()` modules enable insertion of realistic screws and nuts with adjustable clearances. Supports optional modeled threads, material color macros, and a consistent origin convention for simple assembly integration.

- **ScrewsMetric**

  - **Repo:** [More-Wrong/ScrewsMetric](https://github.com/More-Wrong/ScrewsMetric)
  - ![Last commit](https://img.shields.io/github/last-commit/More-Wrong/ScrewsMetric)
  - **Description:** Database-driven library of ISO‑standard metric fasteners including bolts, nuts, washers, bearings with precise dimensions, tolerance options, and parameter-driven interfaces for embedding hardware into designs.

- **usagi.scad**

  - **Repo:** [usagi/usagi.scad](https://github.com/usagi/usagi.scad)
  - ![Last commit](https://img.shields.io/github/last-commit/usagi/usagi.scad)
  - **Description:** Japanese-origin OpenSCAD library offering JIS/ISO-compliant parametric modules for bolts, nuts, washers, and structural profiles, emphasizing part fidelity and standards adherence.

- **BOLTS: Open Library of Technical Specifications**

  - [boltsparts/boltsparts](https://github.com/boltsparts/boltsparts)
  - ![Last commit](https://img.shields.io/github/last-commit/boltsparts/boltsparts)
  - **Description:** Standardized library for generating parametric nuts, bolts, washers, and fastener interfaces conforming to ISO/ANSI dimensions, with easy global or local installation.

- **BOLTS (archive)**

  - [boltsparts/BOLTS_archive](https://github.com/boltsparts/BOLTS_archive)
  - ![Last commit](https://img.shields.io/github/last-commit/boltsparts/BOLTS_archive)
  - **Description:** Archive, the repository was renamed a new repository was created. For the new repository some not needed data was stripped and the history rewritten.

### Gears

- **OpenSCAD Gear Generator**

  - **Repo:** [chrisspen/gears](https://github.com/chrisspen/gears)
  - ![Last commit](https://img.shields.io/github/last-commit/chrisspen/gears)
  - **Description:** Full-featured gear toolkit for racks, spur, helical, ring, bevel, worm, and planetary gears; supports DIN-compliant involute profiles, pressure-angle/helix-angle adjustments, herringbone options, and assembled vs. unassembled output.

- **Lens Gears**

  - **Link:** [Jaymis – Lens Gears Blog](https://jaymis.com/2015/11/3d-printable-seamless-friction-fit-lens-gears-for-follow-focus/)
  - **Description:** OpenSCAD script (plus 100 pre-generated STLs) to create friction-fit follow-focus rings for camera lenses (50–100 mm diameters in 0.5 mm steps); includes measurement guidance, shrinkage compensation, and Customizer support for arbitrary sizes.

- **Spherical Bevel Gears**
  - **Repo:** [JediJeremy/BevelGears](https://github.com/JediJeremy/BevelGears)
  - ![Last commit](https://img.shields.io/github/last-commit/JediJeremy/BevelGears)
  - **Description:** Alpha-stage library for generating spherical involute bevel gear pairs in OpenSCAD using list comprehensions; customizable gear geometry for non-planar meshing, requires OpenSCAD 2019.05 or later.

### Bearings & Belts

- **scad_libraries**
  - **Repo:** [phidiasllc/scad_libraries](https://github.com/phidiasllc/scad_libraries)
  - ![Last commit](https://img.shields.io/github/last-commit/phidiasllc/scad_libraries)
  - **Description:** Parametric models for common motion components including ball and roller bearings, timing and V‑belts, pulleys, sprockets, gears, shafts as well as helper modules for groove machining and belt tensioners. Aims to simplify the design of mechanical power-transmission assemblies.

### Pumps

- **Peristaltic Pump (TomHodson)**

  - **Repo:** [TomHodson/Peristaltic-Pump](https://github.com/TomHodson/Peristaltic-Pump)
  - ![Last commit](https://img.shields.io/github/last-commit/TomHodson/Peristaltic-Pump)
  - **Description:** Design files for a 3D‑printable peristaltic pump head optimized for flexible tubing and low-shear fluid handling. Consists of a rotor with an adjustable roller count, the housing with inlet/outlet ports, and mounting flanges.

- **Peristaltic Pump (adricl)**

  - **Repo:** [adricl/peristaltic-pump](https://github.com/adricl/peristaltic-pump)
  - ![Last commit](https://img.shields.io/github/last-commit/adricl/peristaltic-pump)
  - **Description:** Slim peristaltic pump SCAD library providing a compact pump head module with parameterized tube diameter, rotor spacing, and housing thickness for integration into automated fluidic systems.

- **Moineau Pump**
  - **Repo:** [doctek/Moineau-Paste-Extruder](https://github.com/doctek/Moineau-Paste-Extruder)
  - ![Last commit](https://img.shields.io/github/last-commit/doctek/Moineau-Paste-Extruder)
  - **Description:** Parametric progressive‑cavity (Moineau) pump design for paste extrusion. The design consists of the rotor and stator geometries, mounting adapter, and mounting bracket which supports variable pitch, rotor length, and stator thickness for granular control of extrusion flow.

### Funnels & Couplings

- **Cylindrical Couplings**
  - **Repo:** [alexbirklykke/openscad](https://github.com/alexbirklykke/openscad)
  - ![Last commit](https://img.shields.io/github/last-commit/alexbirklykke/openscad)
  - **Description:** Provides two SCAD modules: 1. `funnel()` for smooth tapered transitions between differing diameters and 2. `cylindrical_coupling()` for creating seamless pipe couplings. Parameters include inlet/outlet diameters, length, wall thickness, and optional chamfer/rim details, ideal for fluid or ducting connectors.

### Joints

- **JointSCAD**
  - **Repo:** [HopefulLlama/JointSCAD](https://github.com/HopefulLlama/JointSCAD)
  - ![Last commit](https://img.shields.io/github/last-commit/HopefulLlama/JointSCAD)
  - **Description:** Single-stop library for parametric joinery: includes bridle, dovetail, dowel, finger, mortise & tenon (standard, pinned, shouldered), scarf, and other joint modules. Exposes modular functions (e.g. `dovetailJointA(dimensions, count)`) to split prints and assemble mechanical or woodworking parts precisely.

### Wheels & Pulleys

- **Pulley Models**

  - **Repo:** [ElectricSkateboard/SolidModels](https://github.com/ElectricSkateboard/SolidModels)
  - ![Last commit](https://img.shields.io/github/last-commit/ElectricSkateboard/SolidModels)
  - **Description:** Parametric OpenSCAD models for power‑transmission components as well as motor mounts and sprocket examples for hobby robotics. Features GT2, T‑MXL, XL, HTD pulley profiles with customizable tooth count and belt compatibility.

- **Configurable Wheel**

  - **Repo:** [alexfranke/Highly-Configurable-Wheel](https://github.com/alexfranke/Highly-Configurable-Wheel)
  - ![Last commit](https://img.shields.io/github/last-commit/alexfranke/Highly-Configurable-Wheel)
  - **Description:** STL generator using an OpenSCAD Customizer with 46 parameters to produce versatile wheel and tire designs, adjustable for rim diameter, tread pattern, spoke count, thickness, and hub mounting features.

- **Rover Wheel**

  - **Repo:** [DavidMFlynn/RoverWheel](https://github.com/DavidMFlynn/RoverWheel)
  - ![Last commit](https://img.shields.io/github/last-commit/DavidMFlynn/RoverWheel)
  - **Description:** Complete parametric rover wheel assembly with integrated 60:1 planetary gearbox, motor mount, and low‑res quadrature encoder pockets (7200 counts/rotation), optimized for 3D printing and custom robotics platforms.

- **Filament Tires**
  - **Repo:** [Arcus-3d/FilaMecanum](https://github.com/Arcus-3d/FilaMecanum)
  - ![Last commit](https://img.shields.io/github/last-commit/Arcus-3d/FilaMecanum)
  - **Description:** OpenSCAD source and STL modules for Mecanum‑style wheels using filament loops as tread; generates hub designs and loop patterns that enable omnidirectional movement on flat surfaces.

### Pegboards

- **Skadis Accessories**

  - **Repo:** [franpoli/OpenSCADutil (ikea_skadis_pegboard_accessories)](https://github.com/franpoli/OpenSCADutil/tree/master/ikea_skadis_pegboard_accessories)
  - ![Last commit](https://img.shields.io/github/last-commit/franpoli/OpenSCADutil)
  - **Description:** Parametric library for IKEA Skådis pegboards providing hooks, plates, boxes, racks and tool mounts. Configure cell size, accessory type, wall thickness, chamfers and mounting inset; includes demo files and detailed usage instructions.

- **PegSTR**

  - **Repo:** [MGX3D/pegstr](https://github.com/MGX3D/pegstr)
  - ![Last commit](https://img.shields.io/github/last-commit/MGX3D/pegstr)
  - **Description:** “Pegboard Wizard” generator for standard 1″-spaced US pegboards. Create holders and bins in arbitrary M×N matrices, with round, square or rectangular shapes, strength vs. economy settings, snap‑in features, and adjustable tilt or openness.

- **Peggrid**
  - **Repo:** [ringerc/openscad-pegboard-peggrid](https://github.com/ringerc/openscad-pegboard-peggrid)
  - ![Last commit](https://img.shields.io/github/last-commit/ringerc/openscad-pegboard-peggrid)
  - **Description:** Simple SCAD modules for generating perforated plates or negative peg grids. Customize board dimensions, hole/peg diameter and spacing, square or hex patterns, edge margins, center alignment, and hole depth. This library is ideal for decorative panels, filters, or subtractive modeling.

## 2D Tools

- **PathBuilder**

  - **Repo:** [dinther/pathbuilder](https://github.com/dinther/pathbuilder)
  - ![Last commit](https://img.shields.io/github/last-commit/dinther/pathbuilder)
  - **Description:** SVG‑style path language implemented in OpenSCAD (`m, l, h, v, c, s, q, a`, plus `fillet`, `chamfer`, `forward`, etc.) for building complex 2D outlines or point lists programmatically. Supports mixed absolute/relative commands, customizable curve segmentation, and direct extrusion or mesh generation.

- **SCAD Utils (2D)**

  - **Repo:** [OskarLinde/scad-utils](https://github.com/OskarLinde/scad-utils)
  - ![Last commit](https://img.shields.io/github/last-commit/OskarLinde/scad-utils)
  - **Description:** Lightweight collection of 2D morphology and symmetry operations (`inset`, `outset`, `fillet`, `rounding`, `shell`), plus mirror transforms and utility math modules.

- **SCADTrace**

  - **Repo:** [guyc/scadtrace](https://github.com/guyc/scadtrace)
  - ![Last commit](https://img.shields.io/github/last-commit/guyc/scadtrace)
  - **Description:** Bitmap‑to‑SCAD converter: uses Potrace to vectorize black‑and‑white images into SVG, triangulates via Triangle, and emits optimized `polyhedron()` geometry for embossing or 3D reliefs inside OpenSCAD.

- **LaserCut**

  - **Repo:** [bmsleight/lasercut](https://github.com/bmsleight/lasercut)
  - ![Last commit](https://img.shields.io/github/last-commit/bmsleight/lasercut)
  - **Description:** Modules to flatten 3D OpenSCAD models into laser‑cuttable 2D parts (`lasercutout`, `lasercutoutSquare`, `lasercutoutBox`), complete with tabbing, captive‑nut slots, finger joints and CNC bit corner relief. Generates DXF or flattened SCAD for rapid fabrication.

- **LaserSCAD**
  - **Repo:** [mbugert/laserscad](https://github.com/mbugert/laserscad)
  - ![Last commit](https://img.shields.io/github/last-commit/mbugert/laserscad)
  - **Description:** High‑level API for 2D laser‐cut template generation: wrap 3D parts in `lpart()` and use `make cut`/`make engrave` to auto‐layout DXF/SVG sheets, with kerf compensation, engraving (`lengrave`), slicing (`lslice`), and preview commands via an included Makefile.

## Case & Boxes

- **LaserCut Box**

  - **Repo:** [larsch/lasercut-box-openscad](https://github.com/larsch/lasercut-box-openscad)
  - ![Last commit](https://img.shields.io/github/last-commit/larsch/lasercut-box-openscad)
  - **Description:** Parametric generator for laser‑cut box panels. Specify width, depth, height, material thickness, finger joint width, and tab spacing. Outputs flattened panels ready for DXF export or laser‑cut workflows, including optional lid and ventilation slot features.

- **Shimon Box**

  - **Repo:** [ubitux/shimonbox](https://github.com/ubitux/shimonbox)
  - ![Last commit](https://img.shields.io/github/last-commit/ubitux/shimonbox)
  - **Description:** Customizable electronics enclosure originally for the Shimon musical instrument. Offers configurable wall thickness, mounting standoffs, cable cutouts, and snap‑fit lid designs. Designed for easy adaptation to other PCB layouts via parameter file.

- **Parametric Case**

  - **Repo:** [eclecticc/ParametricCase](https://github.com/eclecticc/ParametricCase)
  - ![Last commit](https://img.shields.io/github/last-commit/eclecticc/ParametricCase)
  - **Description:** Toolkit for creating versatile electronics enclosures. Includes modules for base, lid, panels, cutouts (USB, HDMI, buttons), snap clips, and mounting rails. Parameters cover wall thickness, corner radii, cutout positions, and fastening options.

- **Dovetail Cases**

  - **Repo:** [cfinke/OpenSCAD-Dovetails](https://github.com/cfinke/OpenSCAD-Dovetails)
  - ![Last commit](https://img.shields.io/github/last-commit/cfinke/OpenSCAD-Dovetails)
  - **Description:** Produces precision dovetail‑style box joints for wooden or printed cases. Functions include `dovetail_joint()` and `dovetail_case()`, with adjustable dovetail angle, board thickness, slot width, and chamfer options for seamless assembly.

- **SeedStack**

  - **Repo:** [apollo-ng/seedstack](https://github.com/apollo-ng/seedstack)
  - ![Last commit](https://img.shields.io/github/last-commit/apollo-ng/seedstack)
  - **Description:** Stackable seed incubation and sprouting trays. Parametric design for tray dimensions, mesh support, drainage holes, and stack spacing. Optimized for 3D printing with interlocking features and consistent alignment.

- **PCB Fixture**

  - **Repo:** [gskielian/PCB-Fixture-Generator](https://github.com/gskielian/PCB-Fixture-Generator)
  - ![Last commit](https://img.shields.io/github/last-commit/gskielian/PCB-Fixture-Generator)
  - **Description:** Automates creation of PCB holding jigs and fixtures. Generates drill guides, alignment pins, clamp slots, and labeling overlays based on board outline and drill file. Built with SCons for configurable, repeatable fixture builds.

- **PCB Boxes**

  - **Repo:** [eyal0/openscad-pcb-boxes](https://github.com/eyal0/openscad-pcb-boxes)
  - ![Last commit](https://img.shields.io/github/last-commit/eyal0/openscad-pcb-boxes)
  - **Description:** Configurable enclosure generator for PCBs, with parameters for board dimensions, wall thickness, standoffs, mounting holes, and cutouts; integrates with SCons for automated builds and variant outputs.

## Raspberry Pi Models

- **OpenSCAD Raspberry Pi Library**

  - **Repo:** [RigacciOrg/openscad-rpi-library](https://github.com/RigacciOrg/openscad-rpi-library)
  - ![Last commit](https://img.shields.io/github/last-commit/RigacciOrg/openscad-rpi-library)
  - **Description:** A set of SCAD modules modeling various Raspberry Pi boards (Model A+, B v2, 3B+, 4B) and common add‑ons (LCD panels, sensor modules, HDD shields). Provides accurate board outlines, mounting hole locations, and component clearances to aid in rapid case and enclosure prototyping.

- **Raspi3-Airchannel**

  - **Repo:** [pinae/Raspi3-Airchannel](https://github.com/pinae/Raspi3-Airchannel)
  - ![Last commit](https://img.shields.io/github/last-commit/pinae/Raspi3-Airchannel)
  - **Description:** Two‑part 3D‑printable air channel designed to mount a 60 mm fan on a Raspberry Pi 3 Model B+. Channels airflow over the SoC and underside memory chip, supports optional heatsinks, and prints without support when top rotated 180°.

- **OpenSCAD Library (RPi & Servos)**

  - **Repo:** [process1183/openscad-library](https://github.com/process1183/openscad-library)
  - ![Last commit](https://img.shields.io/github/last-commit/process1183/openscad-library)
  - **Description:** Defines mechanical parameters and simple 3D modules for RPi boards (including 4 B and camera HDMI extension) and Hitec HS‑85MG micro servo. Variables cover board dimensions, port locations, mounting hole spacing, and servo horn geometry.

- **Raspberry-Pi-OpenSCAD-Model**
  - **Repo:** [TomHodson/Raspberry-Pi-OpenSCAD-Model](https://github.com/TomHodson/Raspberry-Pi-OpenSCAD-Model)
  - ![Last commit](https://img.shields.io/github/last-commit/TomHodson/Raspberry-Pi-OpenSCAD-Model)
  - **Description:** Simplified SCAD representations of Raspberry Pi boards based on published mechanical data and direct measurements. Provides `Raspberry_Pi_4B()` and common PCB outline modules for quick placement into larger assemblies or enclosures.

## Calendars

- **Configurable Calendar**
  - **Link:** [chrastecky/open-scad-configurable-calendar-3d-model](https://chrastecky.dev/3d-printing/open-scad-configurable-calendar-3d-model)
  - **Description:** A fully scriptable 3D‑printable calendar implemented in OpenSCAD. Uses Zeller’s Congruence and custom leap‑year logic to calculate weekday offsets for any year. Offers parameters for start/end month, months‑per‑row layout, grid dimensions, text size, holiday and weekend highlighting, multi‑material color layering, translation/localization of labels, print quality (segment resolution), and configurable magnet or screw holes for mounting on walls or fridges.

## Novel & Interesting

- **Simple Paste Extruder**

  - **Repo:** [keesj/simple-paste-extruder](https://github.com/keesj/simple-paste-extruder) ![Last commit](https://img.shields.io/github/last-commit/keesj/simple-paste-extruder)
  - **Description:** Minimalistic “direct‑drive” extruder for 3D printers using a standard syringe (32 mm OD), M8 bolt & nut, and a 28BYJ‑48 stepper. All non‑printed parts are low‑cost and readily available; the SCAD script generates rack‑and‑pinion gears and frames via MCAD submodule.

- **ThrustMeter Assembly**

  - **Repo:** [AndKe/ThrustMeter](https://github.com/AndKe/ThrustMeter) ![Last commit](https://img.shields.io/github/last-commit/AndKe/ThrustMeter)
  - **Description:** Complete thrust‑test rig using OpenSCAD for the 3D‑printed sled and mount, paired with an Arduino‑based force sensor and DataExplorer logging. Measures thrust, power (g/W), and efficiency of RC motors, propellers, and ESCs with vibration‑damped sled mounting.

- **KeyV2**

  - **Repo:** [rsheldiii/KeyV2](https://github.com/rsheldiii/KeyV2) ![Last commit](https://img.shields.io/github/last-commit/rsheldiii/KeyV2)
  - **Description:** Extensive parametric keycap library supporting Cherry and Alps stems, multiple profiles (SA, DSA, DCS, G20, Hi‑Pro, OEM), custom legends, artisan inserts, and full‑layout generation. Includes Customizer support, modifier chains, and example layouts (60%, Ergodox).

- **LockPickr**

  - **Repo:** [spookey/lockpickr](https://github.com/spookey/lockpickr) ![Last commit](https://img.shields.io/github/last-commit/spookey/lockpickr)
  - **Description:** Work‑in‑progress OpenSCAD models for laser‑cut lock‑picking tools (picks, bows, triangles). Provides parametric handle, pick profile, and demo visuals; aims to generate STL or DXF outlines for hobbyist tool creation.

- **Parametric Switch Holder**

  - **Repo:** [qwelyt/Parametric-switch-holder](https://github.com/qwelyt/Parametric-switch-holder) ![Last commit](https://img.shields.io/github/last-commit/qwelyt/Parametric-switch-holder)
  - **Description:** Customizable keyboard switch station generating lube trays, switch testers, or storage grids in arbitrary M×N layouts. Adjust cell spacing, switch type (Cherry/Alps), plate thickness, and optional “puzzle” interlocking legs for compact organization.

- **Aircores**

  - **Repo:** [HelsinkiHacklab/aircores](https://github.com/HelsinkiHacklab/aircores)
  - ![Last commit](https://img.shields.io/github/last-commit/HelsinkiHacklab/aircores)
  - **Description:** Parametric OpenSCAD models and Arduino code for building air‑core gauge coilforms and their winding machines. Includes printable coilforms, a “spooler” assembly for automated winding, and PWM/I²C driver firmware for measurement and control.

- **Wire Dispenser**

  - **Repo:** [tuna-f1sh/wire-dispenser](https://github.com/tuna-f1sh/wire-dispenser)
  - ![Last commit](https://img.shields.io/github/last-commit/tuna-f1sh/wire-dispenser)
  - **Description:** Laser‑cut reel dispenser for wiring projects. Fully configurable for any number and size of spools, with slot geometry tuning. Uses OpenSCAD’s `projection()` to generate flat DXF panels for CNC cutting.

- **Bottle Engraver**

  - **Repo:** [farbro/bengraver](https://github.com/farbro/bengraver)
  - ![Last commit](https://img.shields.io/github/last-commit/farbro/bengraver)
  - **Description:** Open‑source CNC bottle engraver design. Guides laser or rotary tool around a bottle’s curvature to etch graphics. Includes SCAD and FreeCAD files, drill guides, STL parts, and a detailed build thesis.

- **Möbius Patterns**

  - **Repo:** [oherrala/openscad-moebius](https://github.com/oherrala/openscad-moebius)
  - ![Last commit](https://img.shields.io/github/last-commit/oherrala/openscad-moebius)
  - **Description:** Scripts for creating Möbius strips and umbilic tori with customizable twist count, tube radius, and mesh resolution. Provides ready‑to‑print STLs and sample visuals for mathematical and decorative modeling.

- **OpenSCADObjects**

  - **Repo:** [jeffbarr/OpenSCADObjects](https://github.com/jeffbarr/OpenSCADObjects)
  - ![Last commit](https://img.shields.io/github/last-commit/jeffbarr/OpenSCADObjects)
  - **Description:** A curated collection of over 75 handcrafted parametric, customizer‑enabled objects designed for easy adaptation and rapid FDM printing. Features various geometric tessellations, functional parts, and decor models.

- **Ventilator (COSV‑CAM)**

  - **Link:** [COSV - Cam Open Source Ventilator](https://hackaday.io/project/170507-cosv-cam-open-source-ventilator)
  - **Description:** Roller‑cam‑based BVM ventilator designed for COVID‑19 relief. Combines laser‑cut frames and 3D‑printed parts to compress bag‑valve masks, using Arduino‑driven feedback for assisted ventilation modes. Cost‑effective (~$220) and quick‑build solution.

- **openJoystick**

  - **Repo:** [tjhowse/OpenJoystick](https://github.com/tjhowse/OpenJoystick)
  - ![Last commit](https://img.shields.io/github/last-commit/tjhowse/OpenJoystick)
  - **Link:** [YouTube Demo](https://www.youtube.com/watch?v=GIY6-3KwIS8&list=PLC66292176B625E2A)
  - **Description:** Cross-platform application that captures and visualizes gamepad/joystick input in real time making it ideal for driving interactive, input-based parametric models or debugging control schemes in OpenSCAD workflows.

- **PistonPen**

  - **Repo:** [sanja-byelkin/SimplePistonPen](https://github.com/sanja-byelkin/SimplePistonPen)
  - ![Last commit](https://img.shields.io/github/last-commit/sanja-byelkin/SimplePistonPen)
  - **Description:** Fully parametric, printable piston mechanism that converts linear motion into ink deposition. It includes the cylinder, piston, pen-holder, and mounting brackets with adjustable dimensions and seal taper settings for smooth fluid-driven writing.

<br/>

---

<br/>

## Obsolete (Unmaintained)

> Anything not working in stable or nightly builds.

- **ScaraOne**

  - **Repo:** [robdobsn/ScaraOne](https://github.com/robdobsn/ScaraOne)
  - ![Last commit](https://img.shields.io/github/last-commit/robdobsn/ScaraOne)
  - **Description:** Parametric OpenSCAD implementation of a single‑arm SCARA robot, including modules for the base, rotary joint, arm link, and end‑effector, intended for rapid prototyping of articulated robotic arms.

- **nerdata**

  - **Repo:** [drigberg/nerdata](https://github.com/drigberg/nerdata)
  - ![Last commit](https://img.shields.io/github/last-commit/drigberg/nerdata)
  - **Description:** JavaScript/TypeScript library that generates random names, places, items, species, and quotes from various sci‑fi and fantasy universes (Star Wars, Dune, LotR, etc.), with include/exclude filtering and zero external dependencies.

- **MOST SCAD Libraries**

  - **Repo:** [mtu-most/most-scad-libraries](https://github.com/mtu-most/most-scad-libraries)
  - ![Last commit](https://img.shields.io/github/last-commit/mtu-most/most-scad-libraries)
  - **Description:** Suite of SCAD modules used in the MOST project: NEMA17 stepper mounts, planetary gearbox mechanisms, belt and pulley profiles, bearing models, fasteners, calibration blocks, and SCAD‑based font rendering.

- **Magpie**

  - **Repo:** [sjkelly/Magpie](https://github.com/sjkelly/Magpie)
  - ![Last commit](https://img.shields.io/github/last-commit/sjkelly/Magpie)
  - **Description:** “Vitamins” library and BOM generator for OpenSCAD: provides parametric hardware component models (electronics, fasteners) and utilities to assemble a bill of materials alongside your designs.

- **BezierScad**

  - **Repo:** [chadkirby/BezierScad](https://github.com/chadkirby/BezierScad)
  - ![Last commit](https://img.shields.io/github/last-commit/chadkirby/BezierScad)
  - **Description:** Library of generalized Bézier curve functions for OpenSCAD such as `BezWall`, `BezLine`, `BezArc` which support arbitrary control‑point counts, width/height interpolation, and 2D/3D extrusion workflows.

- **GraphSCAD**

  - **Repo:** [graphscad/graphscad](https://github.com/graphscad/graphscad)
  - ![Last commit](https://img.shields.io/github/last-commit/graphscad/graphscad)
  - **Description:** Nodal editor that exports OpenSCAD scripts: build graphs of transform and shape nodes (gears, pulleys, boxes, look‑at, etc.), manage world/local/object coordinate spaces, and embed graph metadata in SCAD comments.

- **OpenSCAD Model Library**

  - **Repo:** [cznewt/openscad-model-library](https://github.com/cznewt/openscad-model-library)
  - ![Last commit](https://img.shields.io/github/last-commit/cznewt/openscad-model-library)
  - **Description:** Basic library of composite shapes and extrusion utilities for modular 3D objects; includes modules for Raspberry Pi enclosures, HC‑SR04 sensor mounts, primitive combinations, and utility functions.

- **OpenSCAD-Modules**

  - **Repo:** [snemetz/OpenSCAD-Modules](https://github.com/snemetz/OpenSCAD-Modules)
  - ![Last commit](https://img.shields.io/github/last-commit/snemetz/OpenSCAD-Modules)
  - **Description:** Personal collection powering the “Data Center in a Box” project: modular case and shelf designs, PCB mount plates, standoff libraries, pattern generators, and accessory modules.

- **PyCAD**
  - **Repo:** [Verkhovskaya/PyCAD](https://github.com/Verkhovskaya/PyCAD)
  - ![Last commit](https://img.shields.io/github/last-commit/Verkhovskaya/PyCAD)
  - **Description:** Python library for generating 3D models via an OpenSCAD backend: use the `Figure` API to define lines, shapes, and transformations, auto‑generate SCAD scripts, launch the GUI, and export STL files.

<br/>

---

<br/>

[![Star History Chart](https://api.star-history.com/svg?repos=elasticdotventures/awesome-openscad&type=Date)](https://star-history.com/#awesome-openscad&Date)
