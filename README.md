# Awesome CG / VFX Pipeline
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-27-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

List of open-source technologies that help in the process of building a
pipeline for CG or VFX productions.

Any contribution is welcome!

# Summary

- [Digital Content Creation Software (DCCs)](#digital-content-creation-software-dccs)
  - [2D](#2d)
  - [3D](#3d)
  - [3D realtime engines](#3d-realtime-engines)
  - [Audio](#audio)
  - [Rendering Engines](#rendering-engines)
  - [Photogrammetry](#photogrammetry)
  - [Photography](#photography)
  - [Video](#video)
  - [UV/Unwrap Library](#uvunwrap-library)
  - [Tools](#tools)
  - [Writing](#writing)
- [Libraries](#libraries)
  - [File path](#file-path)
  - [Ui](#ui)
  - [CG Software API](#cg-software-api)
  - [Geometry](#geometry)
  - [Colors](#colors)
  - [Shaders](#shaders)
- [File formats](#file-formats)
- [File transfer](#file-transfer)
- [Job schedulers](#job-schedulers)
- [Package managers](#package-managers)
- [Asset managers](#asset-managers)
- [Production managers](#production-managers)
- [Content validation](#content-validation)
- [Docker images](#docker-images)
  - [Misc](#misc)
- [Plugins](#plugins)
- [IDE](#ide)
  - [Pycharm](#pycharm)
  - [SublimeText](#sublimetext)
  - [Vim](#vim)
  - [VSCode](#vscode)
- [Databases](#databases)
  - [Graph](#graph)
  - [Relational](#relational)
  - [Document-based](#document-based)
- [Monitoring Web Services](#monitoring-web-services)
- [Communities](#communities)
- [Resources / Tutorials](#resources--tutorials)
- [Free music for showreel](#free-music-for-showreel)
- [Contributors ✨](#contributors-)

## Digital Content Creation Software (DCCs)

### 2D

* [Allusion](https://allusion-app.github.io) - Allusion is a tool to help you organize your **Visual Library**. It is a complementary tool to PureRef or another Board tool, like [PureRef](https://www.pureref.com/) or [Kuadro](http://www.kruelgames.com/tools/kuadro/) - no open source software - or [BeeRef](#2d).
* [BeeRef](https://github.com/rbreu/beeref) - A simple Reference Image Viewer.
* [Cascade Image Editor](https://github.com/ttddee/Cascade) - A node-based image editor with GPU-acceleration
* [Gimel Studio](https://github.com/GimelStudio/GimelStudio) - Cross-platform, non-destructive, node based 2D image graphics editor
* [Imogen](https://github.com/CedricGuillemet/Imogen) - GPU Texture generator using dear imgui for UI
* [Inkscape](https://inkscape.org/) - Professional quality vector graphics softwar
* [Krita](https://krita.org) - A professional painting program
* [Materia](https://github.com/Metric/Materia) - An open source alternative to Substance Designer written in C#
* [MyPaint](https://github.com/mypaint/mypaint) - Graphics editor for digital painters with a focus on painting rather than image manipulation or post processing
* [Opentoonz](https://opentoonz.github.io/) - Animation production software
* [Pencil2D](https://www.pencil2d.org/) - An easy, intuitive tool to make 2D hand-drawn animations, the best way to visualize your story
* [Storyboarder](https://wonderunit.com/storyboarder/) - Storyboard editor
* [Synfig](https://www.synfig.org/) - 2D animation software
* [TexGraph](https://galloscript.itch.io/texgraph) - A procedural texture creation tool that let you create textures by connecting nodes in a graph
* [The Gimp](https://www.gimp.org) - A cross-platform image editor

### 3D

* [Animation Nodes](https://github.com/JacquesLucke/animation_nodes) - A node based visual scripting system designed for motion graphics in Blender
* [ArmorPaint](https://armorpaint.org/) - A stand-alone software designed for physically-based texture painting
* [Blender](https://blender.org) - Modeling and animation
* [Dust3D](https://dust3D.org) - Dust3D is brand new 3D modeling software. It lets you create watertight 3D models in seconds. Use it to speed up character modeling for games, 3D printing, and so on. [Source are available on Github](https://github.com/huxingyi/dust3d).
* [F3D](https://f3d-app.github.io/f3d/) - Fast and minimalist 3D viewer, with animation, thumbnails and many file formats support.
* [FragM](https://github.com/3Dickulus/FragM) - Mikael Hvidtfeldt Christensen's Fragmentarium fork representing a compilation of features and fixes
* [Gaffer](https://github.com/GafferHQ/gaffer) - Gaffer is a great toolbox, it's a VFX application that enables look developers, lighters, and compositors to easily build, tweak, iterate, and render scenes. 
* [glChAoS.P](https://github.com/BrutPitt/glChAoS.P) - RealTime 3D Strange Attractors scout on GPU
* [Mandelbulb3D](https://github.com/thargor6/mb3d) - A program designed for the Windows platform, for generating 3D views of different fractals
* [Mandelbulber v2](https://github.com/buddhi1980/mandelbulber2) - Mandelbulber creatively generates three-dimensional fractals
* [MeshLab](https://www.meshlab.net/) - System for processing and editing 3D triangular meshes
* [Möbius Modeller](http://design-automation.net/software/mobius/index.html) -  End-user visual programming in the browser for automating complex tasks
* [Nodi](https://github.com/Nodi3d/nodi) - Nodi is an online node-based geometry design tool, it's a web tool
* [Penzil](https://github.com/jacopocolo/Penzil) - A web application to sketch in 3d made in three.js and Vue
* [Possumwood](https://github.com/martin-pr/possumwood) - A graph-based procedural sandbox, implementing concepts of graph-based visual programming in a simple interface
* [Sorcar](https://aachman98.itch.io/sorcar) - A procedural modeling node-based system which utilises Blender and its Python API to create a visual programming environment for artists and developers
* [Sverchok](https://github.com/nortikin/sverchok/) - A powerful parametric Blender tool for architects, allowing geometry to be programmed visually with nodes
* [Tissue](https://github.com/alessandro-zomparelli/tissue) - Blender's add-on for computational design
* [VFX Fractal Toolkit](https://github.com/jtomori/vft) - Set of tools for generating fractal and generative art
* [Wings 3D](http://www.wings3d.com/) - An advanced subdivision modeler that is both powerful and easy to use
* [ZENO](https://github.com/zenustech/zeno) - Node based 3D system able to produce cinematic physics effects at High Efficiency

### 3D realtime engines

* [Armory](https://armory3d.org) - 3D engine with Blender integration focused on portability, minimal footprint and performance
* [Babylon.js](http://www.babylonjs.com/) - WebGL engine
* [Bevy](https://bevyengine.org/) - A refreshingly simple data-driven game engine built in Rust
* [Filament](https://github.com/google/filament) - PBR engine
* [Fusee](https://github.com/FUSEEProjectTeam/Fusee/) - A multiplatform 3D C# realtime engine with a strong emphasis on content transformation and manipulation
* [Godot](https://godotengine.org/) - C++ based 2D/3D realtime engine (PC, console, mobile, HMTL5)
* [Material Maker](https://rodzilla.itch.io/material-maker) - A procedural materials authoring tool, based on the Godot Engine
* [Neo Axis Engine](https://github.com/NeoAxis/NeoAxisEngine) - NeoAxis Engine is an integrated development environment with built-in 3D and 2D game engine.
* [Ogre](https://www.ogre3d.org/) - Open source graphical rendering engine
* [Overload](https://github.com/adriengivry/Overload) - 3D Game engine with editor
* [Panda3d](https://www.panda3d.org/) - Python based 3d Engine (PC)
* [Stride](https://stride3d.net/) - Game engine dedicated tor realistic rendering and VR, develop with a C# techno.
* [Three.js](https://threejs.org/) - WebGL engine
  * [Procedural GL JS](https://github.com/felixpalmer/procedural-gl-js) - Based on Three.js, this framework is
   dedicated to generate a 3D Map experience on a web
   service.
* [Unreal Engine](https://www.unrealengine.com/) - C++ based 2D/3D realtime engine (PC, console, mobile, HMTL5)
* [UPBGE](https://github.com/UPBGE/upbge) - Integrated game engine in Blender
* [Vengi](https://mgerhardy.github.io/engine/) - A C++ voxel game engine

### Audio

* [Ardour](https://github.com/Ardour/ardour) - Record, Edit, and Mix on Linux, macOS and Windows
* [helio.fm](https://github.com/helio-fm/helio-workstation) - One music sequencer for all major platforms, desktop and mobile
* [Jam](https://github.com/jam-systems/jam) - open source alternative to Clubhouse, Twitter Spaces and similar audio spaces. Create audio rooms that can be used for panel discussions, jam sessions, free flowing conversations, debates, theatre plays, musicals and more.
* [LMSS](https://github.com/LMMS/lmms) - Cross-platform music production software
* [OpenAudio](http://openaudio.webprofusion.com/) - A list of open-source VST (and other format) plugin/app projects
* [zrythm](https://github.com/zrythm/zrythm) - a highly automated and intuitive digital audio workstation

### Rendering Engines

* [AppleSeed](https://appleseedhq.net/) - Physically-based global illumination rendering engine
* [Cycle](https://www.cycles-renderer.org/) - Physically based production renderer developed by the Blender project.
* [LuxCoreRender](https://luxcorerender.org/) - Physically-based and unbiased rendering engine
* [Radeon ProRender](https://www.amd.com/en/technologies/radeon-prorender) Physically-based engine, product by AMD. 

### Photogrammetry

* [AliceVision](https://alicevision.org/) - Photogrammetric Computer Vision Framework
  * [Meshroom](https://github.com/alicevision/meshroom) - 3D Reconstruction Software
* [COLMAP](https://colmap.github.io/) - A general-purpose Structure-from-Motion (SfM) and Multi-View Stereo (MVS) pipeline with a graphical and command-line interface
* [openMVG](https://openmvg.readthedocs.io/en/latest/) - A library for computer-vision scientists and targeted for the Multiple View Geometry community

### Photography

* [Darktable](https://www.darktable.org/) - Photography workflow application and raw developer
* [dcraw](https://www.dechifro.org/dcraw/) - A tool that decodes any raw image from any digital camera on any computer running any operating system
* [RawTherapee](https://github.com/Beep6581/RawTherapee) - free, cross-platform raw image processing program

### Video

* [CasparCG](https://github.com/CasparCG) - A Windows and Linux software used to play out professional graphics, audio and video to multiple outputs as a layerbased real-time compositor
* [DJV](https://darbyjohnston.github.io/DJV/) - Professional review software for VFX, animation, and film production
* [ffmpeg](https://ffmpeg.org/) - A complete, cross-platform solution to record, convert and stream audio and video
* [GStreamer](https://gstreamer.freedesktop.org/) - Pipeline-based multimedia framework that links together a wide variety of media processing systems to complete complex workflows
* [Jitsi](https://github.com/jitsi) - Secure, Simple and Scalable Video Conferences that you use as a standalone app or embed in your web application.
* [Kdenlive](https://www.kdenlive.org) - Video editing software based on the MLT Framework, KDE and Qt
* [MediaPipe](https://mediapipe.dev/) - Cross-platform, customizable ML solutions for live and streaming media
* [mrViewer](https://mrviewer.sourceforge.io/) - The Professional Flipbook, Video and Audio Player
* [Natron](https://natron.fr) - Open Source Compositing Software For VFX and Motion Graphics
* [OBS](https://github.com/obsproject/obs-studio) - software designed for capturing, compositing, encoding, recording, and streaming video content, efficiently.
* [Olive](https://www.olivevideoeditor.org/) - Non-linear video editor aiming to provide a fully-featured alternative to high-end professional video editing software
* [OpenShot](https://github.com/OpenShot/openshot-qt) - award-winning free and open-source video editor for Linux, Mac, and Windows, and is dedicated to delivering high quality video editing and animation solutions to the world.
* [qctools](http://bavc.github.io/qctools/) - A free and open source software tool that helps users analyze and understand their digitized video files through use of audiovisual analytics and filtering
* [Shotcut](https://www.shotcutapp.com/) - A free, open source, cross-platform video editor
* [tlRender](https://github.com/darbyjohnston/tlRender) - timeline render, is an early stage project for rendering editorial timelines
* [UltraGrid](https://github.com/CESNET/UltraGrid) - UltraGrid low-latency audio and video network transmission system

### UV/Unwrap library

* [Thekla atlas](https://github.com/Thekla/thekla_atlas) | This tool performs mesh segmentation, surface parameterization, and chart packing.
* [xatlas](https://github.com/jpcy/xatlas) | Fork from [theakla atlas](https://github.com/Thekla/thekla_atlas), it's a library to generate an UV for -example- lightmap uv.

### Tools

A set of small tools, DCC addons, python library... to complete or add feature on DCC softwares.
* [Capsule](https://github.com/Takanu/Capsule) - Blender addon to export, manage and automate to shared between blender and Unreal/Unity or other realtime engine. 
* [Genetic Drawing](https://github.com/anopara/genetic-drawing) - Python library to generate a stylised rendering from an image 
* [Glsl Texture](https://github.com/patriciogonzalezvivo/glslTexture) - Create textures from Glsl fragment shaders on Blender (2.8)
* [OD CopyPasteExternal](https://github.com/heimlich1024/OD_CopyPasteExternal) - Tool to easily copy/paste a geometry across 3D application like Blender <> 3DS Max <> Maya <> ... <> and more.
* [UE4 Env. project](https://github.com/UE4-OceanProject/Environment-Project) - An Environment Simulation project for Unreal Engine 4.

### Writing

* [Ink](https://github.com/inkle/ink) - open source scripting language for writing interactive narrative.

## Libraries

### File path

* [Clique](https://gitlab.com/4degrees/clique) - Another Python module for file sequence parsing and formatting
* [Fileseq](https://github.com/sqlboy/fileseq) - Frame ranges and file sequences parsing
* [gofileseq](https://github.com/justinfx/gofileseq) - A Golang port of the library above
* [Lucidity](http://lucidity.readthedocs.io/en/latest/) - String/filepath templates system inspired by SGTK's template mechanisms
* [pyseq](https://github.com/rsgalloway/pyseq) - Another Python module for file sequence parsing and serialization

### UI

* [NodeGraphQt](https://github.com/jchanvfx/NodeGraphQt) - Node graph for Qt
* [Nodz](https://github.com/LeGoffLoic/Nodz) - Node generator for Qt
* [Qt.py](https://github.com/mottosso/Qt.py) - Qt versions abstraction
* [QtWebengine](https://github.com/qt/qtwebengine) - Render web content in Qt
* [SceneGraph](https://github.com/mfessenden/SceneGraph) - Ui for scene graph
* [Riffle](https://gitlab.com/4degrees/riffle) - A filesystem browser for PySide supporting sequences grouping
* [Thonside](https://github.com/col-one/thonside) - Python console for Qt apps

### CG Software API

* [CGCmake](https://github.com/chadmv/cgcmake) - CMake modules for CG apps
* [Cortex](https://github.com/ImageEngine/cortex) - Libraries for VFX software development
* [Cross3D](https://github.com/blurstudio/cross3d) - Scene and node management abstraction
* [ExoCortex for Max 2018](https://github.com/unit-image/ExocortexCrate) - ExoCortex ported to Max 2018
* [mGui](https://github.com/theodox/mGui) - Portable pure-python GUI library for Maya
* [minq](https://github.com/theodox/minq) - Maya query language for speeding up common scene operations
* [NXT](https://nxt-dev.github.io/) - A layered code compositing application
* [OpenWalter](https://github.com/rodeofx/OpenWalter) - USD Plugins Arnold, Houdini, Katana, Maya and USD
* [Photoshop Python API](https://github.com/loonghao/photoshop-python-api) - Python API for Photoshop.
* [Py3dsMax](https://github.com/blurstudio/Py3dsMax) - 3dsMax API in Python
* [PyMEL](https://github.com/LumaPictures/pymel) - Python in Maya Done Right
* [Pymiere](https://github.com/qmasingarbe/pymiere) - Python API for Premiere Pro

### Geometry

* [autoremesher](https://github.com/huxingyi/autoremesher) -  Automatic quad remeshing tool 
* [Blender Addons](https://github.com/Antonioya/blender) - Helpers for Blender
* [BlenderGIS](https://github.com/domlysz/BlenderGIS) - Geo data importer
* [CGAL](https://www.cgal.org/) - A software project that provides easy access to efficient and reliable geometric algorithms in the form of a C++ library
* [CvWrap](https://github.com/chadmv/cvwrap) - Fast Maya wrap deformer
* [Dem Bones](https://www.ea.com/seed/news/open-source-dem-bones) - A library for skinning decomposition
* [Easy3D](https://github.com/LiangliangNan/Easy3D) - A lightweight, easy-to-use, and efficient C++ library for processing and rendering 3D data 
* [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page) - A C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms
* [Geometry Central](https://geometry-central.net/) - A modern C++ library of data structures and algorithms for geometry processing, with a particular focus on surface meshes
* [Instant Meshes](https://github.com/wjakob/instant-meshes) - Remesher
* [libigl](https://libigl.github.io/) - A simple C++ geometry processing library
* [MakeHuman](http://www.makehumancommunity.org/) - Parametric human character modeling
* [mmg](https://github.com/MmgTools/mmg) - mmg is an open source software for bidimensional and tridimensional surface and volume remeshing
* [Open3D](http://www.open3d.org/) - A Modern Library for 3D Data Processing
* [OpenSubdiv](http://graphics.pixar.com/opensubdiv/docs/intro.html) - A set of open source libraries that implement high performance subdivision surface evaluation on massively parallel CPU and GPU architectures
* [Optimesh](https://github.com/nschloe/optimesh) - Python library to optimise a triangular mesh, remesh with various 
* [Partio](https://www.disneyanimation.com/technology/partio.html) - A unified interface that makes it easier to load, save, and manipulate particle files
* [PCL](https://pointclouds.org/) - A standalone, large scale, open project for 2D/3D image and point cloud processing
* [Polygon Mesh Processing Library](https://www.pmp-library.org/) - A modern C++ open-source library for processing and visualizing polygon surface meshes
* [QHull](https://github.com/qhull/qhull/wiki) - Convex hull generator
* [Quadriflow](https://github.com/hjwdzh/QuadriFlow) - Convert a mesh to a quadrangulation algorithms 
* [Rigify](https://github.com/LesFeesSpeciales/rigify) - Auto-rigging Addon for Blender
* [Simplex](https://github.com/blurstudio/Simplex) - Blendshape Solver
* [SOFA](https://www.sofa-framework.org/) - An efficient framework dedicated to research, prototyping and development of physics-based simulations

### Colors

* [Colour](https://www.colour-science.org/) - An open-source Python package providing a comprehensive number of algorithms and datasets for colour science
* [OpenColorIO](https://opencolorio.org/) ([repo](https://github.com/AcademySoftwareFoundation/OpenColorIO)) - Unified color environment, a complete color management solution geared towards motion picture production with an emphasis on visual effects and computer animation

### Shaders

* [BRDF Explorer](https://github.com/wdas/brdf) - The Disney BRDF Explorer is an application that allows the development and analysis of bidirectional reflectance distribution functions
* [OSL](http://opensource.imageworks.com/?p=osl) - Language to manipulate shaders
* [Ptex](http://ptex.us/) - A texture mapping system developed by Walt Disney Animation Studios for production-quality rendering
* [SeExpr](https://github.com/wdas/SeExpr) - An embeddable, arithmetic expression language that enables flexible artistic control and customization in creating computer graphics images

## File formats

* [ACES](http://www.oscars.org/science-technology/sci-tech-projects/aces) - Color management
* [AL_USDMaya](https://github.com/AnimalLogic/AL_USDMaya) - Represent Maya data in Maya, and USD data in USD
* [Alembic](http://www.alembic.io/) - Animations
* [Assimp](https://www.assimp.org/) - A portable Open-Source library to import various well-known 3D model formats in a uniform manner
* [Cryptomatte](https://github.com/Psyop/Cryptomatte) - Accurate object ID mattes
* [Field3D](https://magnuswrenninge.com/field3d) - An open source library for storing voxel data
* [ImageMagick](https://imagemagick.org/index.php) - Use ImageMagick to create, edit, compose, or convert bitmap images
* [Kiko](https://github.com/Toolchefs/kiko) - DCC-agnostic animation curves storage (works between Maya and Nuke, with more DCCs to come)
* [luma_usd](https://github.com/LumaPictures/luma_usd) -  Plugins for USD
* [MaterialX](https://github.com/materialx/MaterialX) - Materials and look-dev
* [meshio](https://github.com/nschloe/meshio) - Input/output for many mesh formats
* [OpenCV](https://opencv.org/) - An open source computer vision and machine learning software library
* [OpenDCX](http://www.opendcx.org/) ([repo](https://github.com/dreamworksanimation/opendcx)) - C++ extensions for OpenEXR's "deep" file format
* [OpenEXR](http://www.openexr.com/) ([repo](https://github.com/AcademySoftwareFoundation/openexr)) - exceptional image format for visual effects purposes, pioneered by ILM
* [OpenEXRid](https://github.com/MercenariesEngineering/openexrid) - Object isolation
* [OpenImageIO](https://github.com/OpenImageIO/oiio) - A library for reading and writing images in many common and VFX related formats
* [OpenTimelineIO](http://opentimeline.io) ([repo](https://github.com/PixarAnimationStudios/OpenTimelineIO)) - Editorial timeline
* [OpenVDB AX](https://github.com/dneg/openvdb_ax) - Fast expression language for manipulating OpenVDB files
* [OpenVDB](http://www.openvdb.org/) ([repo](https://github.com/AcademySoftwareFoundation/openvdb)) - Volumetric data
* [pfstools](http://pfstools.sourceforge.net/) - A set of command line programs for reading, writing and manipulating high-dynamic range (HDR) images and video frames
* [texture-synthesis](https://github.com/EmbarkStudios/texture-synthesis) - Example-based texture synthesis written in Rust
* [USD Manager](http://www.usdmanager.org/) - Program designed for lightweight browsing, managing, and editing of Universal Scene Description (USD) files
* [USD Shell Extension for Windows](https://github.com/Activision/USDShellExtension) - a full-featured Windows shell extension for giving the File Explorer support for USD thumbnails, side previews and even exposes certain deep metadata to Windows Search
* [usd-arnold](https://github.com/LumaPictures/usd-arnold) - USD Schemas and tools for exchanging Arnold shader information between multiple 3rd party packages
* [usd-noodle](https://github.com/chris-gardner/usd-noodle) - Pretty node graph showing dependencies of a USD file
* [USD-URI-resolver](https://github.com/LumaPictures/usd-uri-resolver) - A generic, URI based resolver for USD, support custom plugins
* [USD](http://graphics.pixar.com/usd/docs/index.html) - Scenes
* [UsdQt](https://github.com/LumaPictures/usd-qt) - Qt components for building custom USD tools

## File transfer
* [rsync](https://github.com/WayneD/rsync) - open source utility that provides fast incremental file transfer. It also has useful features for backup and restore operations among many other use cases.
* [rclone](https://github.com/rclone/rclone) - rsync for cloud storage Google Drive, S3, Dropbox, Backblaze B2, One Drive, Swift, Hubic, Wasabi, Google Cloud Storage, Yandex Files
* [Tsunami](https://sourceforge.net/projects/tsunami-udp/) - high speed file transfer protocol using UDP and TCP for high speed long distance networks
* [UDT](https://udt.sourceforge.io/) - reliable UDP based application level data transport protocol for distributed data intensive applications over wide area high-speed networks
* [WDT](https://github.com/facebookarchive/wdt) -  Warp speed Data Transfer (WDT) is an embeddedable library (and command line tool) aiming to transfer data between 2 systems as fast as possible over multiple TCP paths.

## Job schedulers

* [CGRU](http://cgru.info/) is a CG tools pack that includes AFANASY, a free opensource render farm manager
* [Coalition](http://coalition.readthedocs.io/en/latest/) from Mercenaries Engineering (developers of Guerilla Render)
* [Flamenco](https://www.flamenco.io/) from the Blender Foundation
* [OpenCue](https://opencue.io) ([repo](https://github.com/AcademySoftwareFoundation/OpenCue)) An open source render management system from Sony Imageworks
* [Pandora](https://prism-pipeline.com/pandora/) Open-Source Renderfarm-Manager
* [Plow](https://github.com/chadmv/plow) by Chad Vernon

## Package managers

* [bleeding-rez](https://github.com/mottosso/bleeding-rez) - a very active Rez fork with improved isolation, Windows support and Python 2+3 support
* [conda](https://github.com/conda/conda)
* [Ecosystem](https://github.com/PeregrineLabs/Ecosystem)
* [mamba](https://github.com/mamba-org/mamba) - a faster drop-in replacement for "conda"
* [qip](https://github.com/themill/qip) - Quarantined Installer for Python
* [Rez Packages](https://github.com/predat/rez-packages)
* [Rez](https://github.com/nerdvegas/rez)
* [wiz](https://github.com/themill/wiz)

### Environment Manager

* [Allzpark](https://github.com/mottosso/allzpark) Based on Rez manager, [Allzpark](https://allzpark.com/) can manage
 your software to give an specific software, really usefull with old project. 

## Asset managers

* [Avalon](https://getavalon.github.io)
* [Damas](http://damas-software.org/)
* [Kabaret](https://www.kabaretstudio.com/)
* [OpenPype](https://openpype.io)
* [Plex](https://github.com/richteralexander/plex)
* [Prism](https://prism-pipeline.com/)
* [SnowFS](https://github.com/Snowtrack/SnowFS)
* [TACTIC-Handler](https://github.com/listyque/TACTIC-Handler)

## Production managers

* [Attract](https://attract.studio/) - Production tracking for film makers (Blender Foundation)
* [Kitsu](https://kitsu.cg-wire.com) - For small to mid-size studios
* [Stalker](https://github.com/eoyilmaz/stalker) - Open Source Production Asset Management (ProdAM) Library designed specifically for Animation and VFX Studios.

## Content validation

* [Pyblish](http://pyblish.com/) - A Python framework that brings test-driven development to visual effects and
 triple-A game creation
  * [Blender Pyblish](https://github.com/jasperges/pyblish-blender) - Blender Addon to integrate the Pyblish framework 

## Docker images

* [Animal Logic's USD Docker](https://github.com/AnimalLogic/docker-usd) - A set of docker build scripts which will download all the Open Source packages required to build Pixar's Universal Scene Description, as well as USD itself
* [Deadline](https://github.com/mottosso/docker-deadline) - Docker images for Thinkbox Software Deadline
* [Foundry RLM](https://github.com/tokejepsen/docker-foundry-rlm)
* [Kitsu/Zou](https://github.com/mottosso/docker-cgwire)
* [Maya](https://github.com/mottosso/docker-maya)

### Misc

* [Jean-Paul Start](https://github.com/cube-creative/jeanpaulstart) - Small (with Ansible-like syntax) launcher with GUI
* [WSL Distribution Switcher](https://github.com/RoliSoft/WSL-Distribution-Switcher) - Change the distro behind Windows Subsystem

## Plugins

* [AFX](https://github.com/AuthorityFX/afx-nuke-plugins) - Everyday compositing for Nuke
* [Cmt](https://github.com/chadmv/cmt) - Various Maya tools
* [FTrack Hooks](https://github.com/tokejepsen/ftrack-hooks) Set of plugins for FTrack
* [OnionSkinRenderer](https://github.com/Viele/onionSkinRenderer) - Onion Skin Renderer for Maya
* [Palladio](https://github.com/Esri/palladio) - CityEngine Plugin for Houdini
* [Wiretap](https://github.com/predat/wiretap) - Manage Flame Wiretap database

## IDE

### PyCharm

* [MayaCharm](https://github.com/cmcpasserby/MayaCharm) - Run and edit Maya scripts directly from PyCharm
* [USD](https://github.com/justint/usd-idea) - Plug-in for USD

### SublimeText

* [MariSublime](https://github.com/cg-cnu/marisublime) - Run and edit Mari scripts directly from SublimeText
* [MayaSublime](https://github.com/justinfx/MayaSublime) - Run and edit Maya scripts directly from SublimeText
* [VEX](https://github.com/teared/VEX) - Houdini add-on for Sublime Text

### vim

* [nuke.vim](https://github.com/heavyimage/nuke.vim) - Run and edit Nuke scripts directly from vim

### VSCode

* [blender_vscode](https://github.com/JacquesLucke/blender_vscode) - Visual Studio Code extension for Blender development
* [Blink Script (Nuke) Language Syntax](https://marketplace.visualstudio.com/items?itemName=melmass.blink) ([repo](https://github.com/melMass/vscode-blink.git)) - for syntax highlighting support
* [MayaCode](https://marketplace.visualstudio.com/items?itemName=saviof.mayacode) ([repo](https://github.com/artbycrunk/vscode-maya)) - Maya syntax highlighting support, along with autocomplete commands and send code to maya via command port
* [MayaPort](https://marketplace.visualstudio.com/items?itemName=JonMacey.mayaport) ([repo](https://github.com/NCCA/mayaport)) - Run Maya code from VSCode
* [MEL Language Syntax](https://github.com/sator-imaging/Visual-Studio-Code-MEL-Language.git) ([repo](https://github.com/sator-imaging/Visual-Studio-Code-MEL-Language.git)) - for syntax highlighting support
* [Pixar USD ASCII Language Syntax](https://marketplace.visualstudio.com/items?itemName=AnimalLogic.vscode-usda-syntax) ([repo](https://github.com/AnimalLogic/AL_usd_vscode_extension)) - for syntax highlighting support, courtesy of the folks at Animal Logic
* [SendtoMaya](https://marketplace.visualstudio.com/items?itemName=ivancheung7.sendtomaya) - Alternative to MayaPort, serving the same purpose
* [VEX Language Syntax](https://marketplace.visualstudio.com/items?itemName=melmass.vex) ([repo](https://github.com/melMass/vscode-vex.git)) - for syntax highlighting support

## Databases

### Graph

* [ArangoDB](https://github.com/arangodb/arangodb)
* [Cayley](https://github.com/cayleygraph/cayley)
* [DGraph](https://dgraph.io/)
* [JanusGraph](https://github.com/JanusGraph/janusgraph)
* [Neo4j](https://github.com/neo4j)
* [OrientDB](https://orientdb.com)

### Relational

* [MySQL](http://www.mysql.com)
* [PostgreSQL](https://www.postgresql.org/)

### Document-based

* [Cassandra](http://cassandra.apache.org/)
* [MongoDB](http://www.mongodb.org)

## Monitoring Web Services
Not really efficient, you can find more links on the sys admin awesome list ; [on monitoring](https://github.com/n1trux/awesome-sysadmin#monitoring) or [metric collection](https://github.com/n1trux/awesome-sysadmin#metric--metric-collection)

## Communities

* [3DVF](http://3dvf.com)
* [3DPro](https://3dpro.org)
* [Academy Software Foundation](https://www.aswf.io/get-involved/)
* [Blender Discord (French)](https://discordapp.com/channels/168826665307209728/168826665307209728)
* [CGWire Discord](https://discord.com/invite/VbCxtKN)
* [Houdini Discord](https://discordapp.com/channels/230123485668573184/360768996980555776)
* [od|force](https://forums.odforce.net/)
* [OpenPype Discord](https://discord.gg/sFNPWXG)
* [StudioSysAdmins](http://studiosysadmins.com)
* [Tech-artists.org](http://tech-artists.org)

## Resources / Tutorials

* [cgwiki](http://www.tokeru.com/cgwiki/)
* [Beginning Python For Maya](http://zurbrigg.com/training/beginning-python-for-maya)
* [Blue Sky Studios Tech Blog](https://medium.com/blue-sky-tech-blog)
* [Digital Video Introduction](https://github.com/leandromoreira/digital_video_introduction)
* [Example of Python scripts for 3D Studio Max, Maya and Blender](https://github.com/p4vv37/3D_Software_and_Python/)
* [Les Fées Spéciales Studio Tech Blog](http://lacuisine.tech/)
* [Pipeline Patterns](http://www.pipelinepatterns.com/)
* [Unit Testing in Maya](http://www.chadvernon.com/blog/maya/unit-testing-in-maya/)
* [VFX good night reading](https://github.com/jtomori/vfx_good_night_reading/) - Curated collection of good reading about VFX and CG

## Free music for showreel

* [Music For Vlogs](https://soundcloud.com/freemusicforvlogs)
* [Wowa](https://www.wowa.me/)

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/frankrousseau"><img src="https://avatars1.githubusercontent.com/u/1336623?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Frank Rousseau</b></sub></a><br /><a href="#content-frankrousseau" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/loonghao"><img src="https://avatars1.githubusercontent.com/u/13111745?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Hal</b></sub></a><br /><a href="#content-loonghao" title="Content">🖋</a></td>
    <td align="center"><a href="http://darkvertex.com"><img src="https://avatars0.githubusercontent.com/u/941331?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Alan Fregtman</b></sub></a><br /><a href="#content-darkvertex" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/notawhalevfx"><img src="https://avatars2.githubusercontent.com/u/45572972?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Nikita Musatov</b></sub></a><br /><a href="#content-notawhalevfx" title="Content">🖋</a></td>
    <td align="center"><a href="https://sreenivas.dev"><img src="https://avatars0.githubusercontent.com/u/2767425?v=4?s=100" width="100px;" alt=""/><br /><sub><b>sreenivas alapati</b></sub></a><br /><a href="#content-cg-cnu" title="Content">🖋</a></td>
    <td align="center"><a href="https://artstation.com/artist/stilobique"><img src="https://avatars0.githubusercontent.com/u/3066684?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Stilobique</b></sub></a><br /><a href="#content-stilobique" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/bob-white"><img src="https://avatars0.githubusercontent.com/u/7028615?v=4?s=100" width="100px;" alt=""/><br /><sub><b>bob-white</b></sub></a><br /><a href="#content-bob-white" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://www.nothing-is-3d.com/"><img src="https://avatars0.githubusercontent.com/u/3873421?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Vincent Lamy</b></sub></a><br /><a href="#content-Vinc3r" title="Content">🖋</a></td>
    <td align="center"><a href="http://blog.theodox.com"><img src="https://avatars3.githubusercontent.com/u/4056600?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Steve Theodore</b></sub></a><br /><a href="#content-theodox" title="Content">🖋</a></td>
    <td align="center"><a href="http://www.cube-creative.com/"><img src="https://avatars2.githubusercontent.com/u/26791257?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Cube Creative</b></sub></a><br /><a href="#content-developer-cube-creative" title="Content">🖋</a></td>
    <td align="center"><a href="http://www.bumpybox.com"><img src="https://avatars0.githubusercontent.com/u/1860085?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Toke Jepsen</b></sub></a><br /><a href="#content-tokejepsen" title="Content">🖋</a></td>
    <td align="center"><a href="http://santoshk.dev"><img src="https://avatars3.githubusercontent.com/u/1515991?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Santosh Kumar</b></sub></a><br /><a href="#content-santosh" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/listyque"><img src="https://avatars2.githubusercontent.com/u/13370598?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Alex Miarsky</b></sub></a><br /><a href="#content-listyque" title="Content">🖋</a></td>
    <td align="center"><a href="http://justintennant.me"><img src="https://avatars2.githubusercontent.com/u/7485210?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Justin Tennant</b></sub></a><br /><a href="#content-justint" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://jtomori.github.io"><img src="https://avatars0.githubusercontent.com/u/22801191?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Juraj Tomori</b></sub></a><br /><a href="#content-jtomori" title="Content">🖋</a></td>
    <td align="center"><a href="http://hellozee.dev"><img src="https://avatars1.githubusercontent.com/u/12135951?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Kuntal Majumder</b></sub></a><br /><a href="#content-hellozee" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/jfpanisset"><img src="https://avatars0.githubusercontent.com/u/32653482?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jean-Francois Panisset</b></sub></a><br /><a href="#content-jfpanisset" title="Content">🖋</a></td>
    <td align="center"><a href="http://www.heavyimage.com"><img src="https://avatars0.githubusercontent.com/u/7820487?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jesse Spielman</b></sub></a><br /><a href="#content-heavyimage" title="Content">🖋</a></td>
    <td align="center"><a href="http://www.corentin-charron.com"><img src="https://avatars2.githubusercontent.com/u/4436347?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Corentin</b></sub></a><br /><a href="#content-corentincharron" title="Content">🖋</a></td>
    <td align="center"><a href="https://www.saviof.com"><img src="https://avatars0.githubusercontent.com/u/1092099?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Savio Fernandes</b></sub></a><br /><a href="#content-artbycrunk" title="Content">🖋</a></td>
    <td align="center"><a href="https://in.linkedin.com/in/anvith-shivakumara"><img src="https://avatars3.githubusercontent.com/u/5442547?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Anvith Shivakumara</b></sub></a><br /><a href="#content-anvth" title="Content">🖋</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/aboellinger"><img src="https://avatars0.githubusercontent.com/u/5718135?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Antoine Boellinger</b></sub></a><br /><a href="#content-aboellinger" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/mathbou"><img src="https://avatars1.githubusercontent.com/u/13415583?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Mathieu Bouzard</b></sub></a><br /><a href="#content-mathbou" title="Content">🖋</a></td>
    <td align="center"><a href="http://pype.club"><img src="https://avatars.githubusercontent.com/u/3333008?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Milan Kolar</b></sub></a><br /><a href="#content-mkolar" title="Content">🖋</a></td>
    <td align="center"><a href="https://github.com/mwestphal"><img src="https://avatars.githubusercontent.com/u/3129530?v=4?s=100" width="100px;" alt=""/><br /><sub><b>mwestphal</b></sub></a><br /><a href="#content-mwestphal" title="Content">🖋</a></td>
    <td align="center"><a href="http://eoyilmaz.blogspot.com"><img src="https://avatars.githubusercontent.com/u/1786804?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Erkan Ozgur Yilmaz</b></sub></a><br /><a href="#content-eoyilmaz" title="Content">🖋</a></td>
    <td align="center"><a href="https://mcoliver.com/"><img src="https://avatars.githubusercontent.com/u/622057?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Michael Oliver</b></sub></a><br /><a href="#content-mcoliver" title="Content">🖋</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
