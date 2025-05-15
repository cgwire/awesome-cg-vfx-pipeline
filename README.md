# Awesome CG / VFX Pipeline
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) <!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-28-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

List of open-source technologies that help in the process of building a
pipeline for CG or VFX productions.

Any contribution is welcome!

# Summary

- [Awesome CG / VFX Pipeline](#awesome-cg--vfx-pipeline)
- [Summary](#summary)
  - [Digital Content Creation Software (DCCs)](#digital-content-creation-software-dccs)
    - [2D](#2d)
    - [3D](#3d)
    - [3D realtime engines](#3d-realtime-engines)
    - [Audio](#audio)
    - [Rendering Engines](#rendering-engines)
    - [Photogrammetry](#photogrammetry)
    - [Photography](#photography)
    - [Video](#video)
    - [UV/Unwrap library](#uvunwrap-library)
    - [Tools](#tools)
    - [Low-code platforms](#low-code-platforms)
    - [Writing](#writing)
  - [Libraries](#libraries)
    - [File path](#file-path)
    - [UI](#ui)
    - [CG Software API](#cg-software-api)
    - [Geometry](#geometry)
      - [Remeshing](#remeshing)
    - [Colors](#colors)
    - [Shaders](#shaders)
    - [Denosing](#denosing)
  - [File formats](#file-formats)
    - [USD](#usd)
  - [File transfer](#file-transfer)
  - [Job schedulers](#job-schedulers)
  - [Package managers](#package-managers)
    - [Environment Manager](#environment-manager)
  - [Asset managers](#asset-managers)
  - [Production managers](#production-managers)
  - [Content validation](#content-validation)
  - [Docker images](#docker-images)
    - [Misc](#misc)
  - [Plugins](#plugins)
  - [IDE](#ide)
    - [PyCharm](#pycharm)
    - [SublimeText](#sublimetext)
    - [vim](#vim)
    - [VSCode](#vscode)
    - [VSCodium](#vscodium)
    - [vscode.dev](#vscodedev)
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
* [Cascade Image Editor](https://github.com/ttddee/Cascade) - A node-based image editor with GPU-acceleration.
* [Friction](https://github.com/friction2d/friction) - Friction is a powerful and versatile motion graphics application that allows you to create vector and raster animations for web and video.
* [Gimel Studio](https://github.com/GimelStudio/GimelStudio) - Cross-platform, non-destructive, node based 2D image graphics editor.
* [Imogen](https://github.com/CedricGuillemet/Imogen) - GPU Texture generator using dear imgui for UI.
* [Inkscape](https://inkscape.org/) - Professional quality vector graphics software.
* [Krita](https://krita.org) - A professional painting program.
* [Materia](https://github.com/Metric/Materia) - An open-source alternative to Substance Designer written in C#. *(The project was archived)*.
* [MyPaint](https://github.com/mypaint/mypaint) - Graphics editor for digital painters focusing on painting rather than image manipulation or post-processing.
* [TexGraph](https://galloscript.itch.io/texgraph) - A procedural texture creation tool that lets you create textures by connecting nodes in a graph.
* [The Gimp](https://www.gimp.org) - A cross-platform image editor.
* [VArtiste](https://gitlab.com/zach-geek/vartiste) - WebXR/VR painting, drawing, and image editing app.
* [TerraForge3D](https://jaysmito101.github.io/TerraForge3D/) - A procedural terrain generation and procedural modeling toolkit.
* [G'MIC](https://gmic.eu/) - A full-featured open-source framework for digital image processing.
* [Graphite](https://graphite.rs/) - 2D raster & vector editor that melds traditional layers & tools with a modern node-based procedural workflow.

#### Animation
* [Opentoonz](https://opentoonz.github.io/) - Animation production software.
* [Pencil2D](https://www.pencil2d.org/) - An easy, intuitive tool to make 2D hand-drawn animations, the best way to visualize your story.
* [Storyboarder](https://wonderunit.com/storyboarder/) - Storyboard editor.
* [Synfig](https://www.synfig.org/) - 2D animation software.
* [Tahoma2D](https://tahoma2d.org//) - 2D and Stop Motion Animation Software. [Source on GitHub](https://github.com/tahoma2d/tahoma2d).


### 3D

* [Animation Nodes](https://github.com/JacquesLucke/animation_nodes) - A node-based visual scripting system designed for motion graphics in Blender.
* [ArmorPaint](https://armorpaint.org/) - A stand-alone software designed for physically-based texture painting.
* [Blender](https://blender.org) - Modeling and animation.
    * [Blender Awesome List](https://github.com/agmmnn/awesome-blender) - More addons and resources around Blender in this awesome list. 
    * [Tissue](https://github.com/alessandro-zomparelli/tissue) - Blender's add-on for computational design.
    * [Sverchok](https://github.com/nortikin/sverchok/) - A powerful parametric Blender tool for architects, allowing geometry to be programmed visually with nodes.
    * [Sorcar](https://aachman98.itch.io/sorcar) - A procedural modeling node-based system which utilizes Blender and its Python API to create a visual programming environment for artists and developers
* [Blockbench](https://www.blockbench.net/) - Low-poly 3D modeling, texturing, and animation. Desktop/web.
* [Dust3D](https://dust3D.org) - Dust3D is brand new 3D modeling software. It lets you create watertight 3D models in seconds. Use it to speed up character modeling for games, 3D printing, and so on. [Source are available on GitHub](https://github.com/huxingyi/dust3d).
* [F3D](https://f3d-app.github.io/f3d/) - Fast and minimalist 3D viewer with animation, thumbnails, and many file formats support.
* [FragM](https://github.com/3Dickulus/FragM) - Mikael Hvidtfeldt Christensen's Fragmentarium fork represents a compilation of features and fixes.
* [FreeCAD](https://www.freecad.org/) - Parametric 3D CAD and BIM modeler with FEM support.
* [Gaffer](https://github.com/GafferHQ/gaffer) - Gaffer is a great toolbox, it's a VFX application that enables look developers, lighters, and compositors to easily build, tweak, iterate, and render scenes.
* [Effekseer](https://effekseer.github.io/en/)is a tool that allows easy creation of beautiful particle effects for games and movies.
* [glChAoS.P](https://github.com/BrutPitt/glChAoS.P) - RealTime 3D Strange Attractors scout on GPU.
* [Mandelbulb3D](https://github.com/thargor6/mb3d) - A program designed for the Windows platform for generating 3D views of different fractals.
* [Mandelbulber v2](https://github.com/buddhi1980/mandelbulber2) - Mandelbulber creatively generates three-dimensional fractals.
* [MeshLab](https://www.meshlab.net/) - System for processing and editing 3D triangular meshes.
* [Möbius Modeller](http://design-automation.net/software/mobius/index.html) -  End-user visual programming in the browser for automating complex tasks.
* [Nodi](https://github.com/Nodi3d/nodi) - Nodi is an online node-based geometry design tool, it's a web tool.
* [Penzil](https://github.com/jacopocolo/Penzil) - A web application to sketch in 3d made in three.js and Vue.
* [Possumwood](https://github.com/martin-pr/possumwood) - A graph-based procedural sandbox implementing concepts of graph-based visual programming in a simple interface.
* [SuperSplat](https://github.com/playcanvas/supersplat) - A browser-based tool for inspecting, editing, optimizing and publishing 3D Gaussian Splats.
* [VFX Fractal Toolkit](https://github.com/jtomori/vft) - Set of tools for generating fractal and generative art.
* [Wings 3D](http://www.wings3d.com/) - An advanced subdivision modeler that is both powerful and easy to use.
* [ZENO](https://github.com/zenustech/zeno) - Node-based 3D system that can produce cinematic physics effects at high efficiency.
* [Blackjack](https://github.com/setzer22/blackjack) - A procedural, node-based modeling tool made in Rust.
* [Plasticity](https://github.com/nkallen/plasticity) - A 3d modelling software for concept artists.
* [Threestudio](https://github.com/threestudio-project/threestudio) - A unified framework for 3D content generation.
* [Material Maker](https://rodzilla.itch.io/material-maker) - A procedural materials authoring tool based on the Godot Engine.

### 3D realtime engines

* [A-Frame](https://aframe.io/) - An easy web framework for building 3D/AR/VR experiences.
* [Armory](https://armory3d.org) - 3D engine with Blender integration focused on portability, minimal footprint and performance.
* [Babylon.js](http://www.babylonjs.com/) - WebGL engine.
* [Bevy](https://bevyengine.org/) - A refreshingly simple data-driven game engine built in Rust.
* [Cauldron](https://github.com/GPUOpen-LibrariesAndSDKs/Cauldron) - A simple framework for rapid prototyping on Vulkan or DirectX12.
* [Falcor](https://github.com/NVIDIAGameWorks/Falcor) - A real-time rendering framework supporting DirectX 12 aiming to improve the productivity of research and prototype projects.
* [Filament](https://github.com/google/filament) - PBR engine, available with all platforms (desktop, mobile).
* [Fusee](https://github.com/FUSEEProjectTeam/Fusee/) - A multiplatform 3D C# real-time engine with a strong emphasis on content transformation and manipulation.
* [Godot](https://godotengine.org/) - C++ based 2D/3D realtime engine (PC, console, mobile, HMTL5).
* [Harfang 3D](https://github.com/harfang3d/harfang3d) - C++ 3D visualization library also usable in Python, Lua, and Go (Windows, Linux).
* [Neo Axis Engine](https://github.com/NeoAxis/NeoAxisEngine) - NeoAxis Engine is an integrated development environment with built-in 3D and 2D game engine.
* [Ogre](https://www.ogre3d.org/) - Open source graphical rendering engine.
* [Open 3D Engine](https://www.o3de.org/) - An open-source, real-time 3D development engine.
* [Overload](https://github.com/adriengivry/Overload) - 3D Game engine with editor.
* [Panda3d](https://www.panda3d.org/) - Python based 3d Engine (PC).
* [Stride](https://stride3d.net/) - Game engine dedicated tor realistic rendering and VR, develop with a C# techno.
* [Three.js](https://threejs.org/) - WebGL engine.
  * [Procedural GL JS](https://github.com/felixpalmer/procedural-gl-js) - Based on Three.js, this framework is dedicated to generating a 3D Map experience on a web service.
* [TOOLL3](https://tooll.io/) - Graph-based procedural real-time motion graphics for live performance or rendering.
* [Unreal Engine](https://www.unrealengine.com/) - C++ based 2D/3D realtime engine (PC, console, mobile, HMTL5).
* [UPBGE](https://github.com/UPBGE/upbge) - Integrated game engine in Blender.
* [Vengi](https://mgerhardy.github.io/engine/) - A C++ voxel game engine.

### Audio

* [Ardour](https://github.com/Ardour/ardour) - Record, Edit, and Mix on Linux, macOS and Windows.
* [helio.fm](https://github.com/helio-fm/helio-workstation) - One music sequencer for all major platforms, desktop, and mobile.
* [Jam](https://github.com/jam-systems/jam) - open-source alternative to Clubhouse, Twitter Spaces, and similar audio spaces. Create audio rooms that can be used for panel discussions, jam sessions, free-flowing conversations, debates, theatre plays, musicals, and more.
* [LMSS](https://github.com/LMMS/lmms) - Cross-platform music production software.
* [OpenAudio](http://openaudio.webprofusion.com/) - A list of open-source VST (and other format) plugin/app projects.
* [zrythm](https://github.com/zrythm/zrythm) - a highly automated and intuitive digital audio workstation.

### Rendering Engines

* [AppleSeed](https://appleseedhq.net/) - Physically-based global illumination rendering engine.
* [Aurora](https://github.com/Autodesk/Aurora) - A real-time path tracing renderer that enables fast product visualizations.
* [bgfx](https://github.com/bkaradzic/bgfx) - Cross-platform, graphics API agnostic, "Bring Your Own Engine/Framework" style rendering library.
* [Cycles](https://www.cycles-renderer.org/) - Physically based production renderer developed by the Blender project.
* [Falcor](https://github.com/NVIDIAGameWorks/Falcor) - Falcor is a real-time rendering framework supporting DirectX 12 and Vulkan. It aims to improve productivity of research and prototype projects.
* [kajiya](https://github.com/EmbarkStudios/kajiya) - Experimental real-time global illumination renderer made with Rust and Vulkan.
* [LuxCoreRender](https://luxcorerender.org/) - Physically-based and unbiased rendering engine.
* [Mitsuba](https://www.mitsuba-renderer.org/) - A research-oriented retargetable rendering system, written in portable C++17 on top of the Enoki library.
* [MoonRay](https://openmoonray.org/index) - DreamWorks’ open-source, award-winning, state-of-the-art production MCRT renderer, which has been used on several feature films.
* [OSPRay](https://github.com/ospray/ospray) - An open-source, scalable, and portable ray tracing engine for high-performance, high-fidelity visualization on Intel Architecture CPUs.
* [Pixie](https://github.com/blkdev2/pixie?tab=readme-ov-file) - Pixie is a photorealistic renderer that uses a Pixar's RenderMan-like interface.
* [PBRT](https://github.com/mmp/pbrt-v4/) - Ray tracer from "Physically Based Rendering: From Theory to Implementation" book.
* [POVRay](http://www.povray.org/) - The Persistence of Vision Raytracer.
* [Radeon ProRender](https://www.amd.com/en/technologies/radeon-prorender) Physically-based engine, product by AMD. 
* [Sunflow](https://github.com/fpsunflower/sunflow) - Not maintained, Sunflow is an open source rendering system for photo-realistic image synthesis.
* [Tungsten](https://github.com/tunabrain/tungsten) - High performance physically based renderer in C++11.
* [Yafaray](https://github.com/YafaRay/libYafaRay) - libYafaRay is a free open-source montecarlo raytracing engine released under the LGPL 2.1 license. Raytracing is a rendering technique for generating realistic images by tracing the path of light through a 3D scene. 
* [Yocto/GL](https://github.com/xelatihy/yocto-gl) - A collection of small C++17 libraries for building physically-based graphics algorithms.

### Photogrammetry

* [AliceVision](https://alicevision.org/) - Photogrammetric Computer Vision Framework.
  * [Meshroom](https://github.com/alicevision/meshroom) - 3D Reconstruction Software.
* [COLMAP](https://colmap.github.io/) - A general-purpose Structure-from-Motion (SfM) and Multi-View Stereo (MVS) pipeline with a graphical and command-line interface.
* [fSpy](https://fspy.io/) - Still image camera matching.
  * [fSpy-Blender](https://github.com/stuffmatic/fSpy-Blender) - Official fSpy Blender importer.
  * [GdSpy](https://github.com/Alby90/GdSpy) - Unofficial fSpy importer for Godot.
  * [fSpy-Maya](https://github.com/Nathanieljla/fSpy-Maya) - Unofficial fSpy Maya importer (one of several).
  * [fSync](https://github.com/MatsValgaeren/fSync) - Unofficial fSpy/Maya bridge which also creates projection shaders.
  * [fSpy-USD](https://github.com/Vochsel/fspy-USD) - Unofficial fSpy to USD converter.
* [openMVG](https://openmvg.readthedocs.io/en/latest/) - A library for computer-vision scientists targeted for the Multiple View Geometry community.

### Photography

* [Darktable](https://www.darktable.org/) - Photography workflow application and raw developer.
* [dcraw](https://www.dechifro.org/dcraw/) - A tool that decodes any raw image from any digital camera on any computer running any operating system.
* [RawTherapee](https://github.com/Beep6581/RawTherapee) - free, cross-platform raw image processing program.

### Video

* [Bino](https://github.com/ThreeDeeJay/bino/tree/main) - 3D video player with support for 180°/360° video and Virtual Reality.
* [CasparCG](https://github.com/CasparCG) - A Windows and Linux software used to play out professional graphics, audio, and video to multiple outputs as a layer-based real-time compositor.
* [Cinelerra](https://www.cinelerra-gg.org/) - Cinelerra GG Infinity is a free and open source video editing software for Linux.
* [Dailies](https://github.com/vfxpaco85/dailies/) - Wraps ffmpeg, Nuke, or RV to process video files and image sequences. Integrates with Shotgun, Ftrack, Kitsu.
* [DJV](https://darbyjohnston.github.io/DJV/) - Professional review software for VFX, animation, and film production.
* [ffmpeg](https://ffmpeg.org/) - A complete, cross-platform solution to record, convert and stream audio and video.
* [Flowblade](https://github.com/jliljebl/flowblade/) - Video Editor for Linux.
* [Gyroflow](https://github.com/gyroflow/gyroflow/) - Video stabilization using gyroscope data.
* [GStreamer](https://gstreamer.freedesktop.org/) - Pipeline-based multimedia framework that links together a wide variety of media processing systems to complete complex workflows.
* [Jitsi](https://github.com/jitsi) - Secure, Simple, and Scalable Video Conferences that you use as a standalone app or embed in your web application.
* [Kdenlive](https://www.kdenlive.org) - Video editing software based on the MLT Framework, KDE and Qt.
* [MediaPipe](https://mediapipe.dev/) - Cross-platform, customizable ML solutions for live and streaming media.
* [mrViewer2](https://github.com/ggarra13/mrv2) - The Professional Flipbook, Video and Audio Player.
* [Natron](https://natron.fr) - Open Source Compositing Software For VFX and Motion Graphics.
* [OBS](https://github.com/obsproject/obs-studio) - software designed for capturing, compositing, encoding, recording, and streaming video content efficiently.
* [Olive](https://www.olivevideoeditor.org/) - Non-linear video editor aiming to provide a fully-featured alternative to high-end professional video editing software.
* [OpenShot](https://github.com/OpenShot/openshot-qt) - Award-winning free and open-source video editor for Linux, Mac, and Windows, and is dedicated to delivering high-quality video editing and animation solutions to the world.
* [OpenRV](https://github.com/AcademySoftwareFoundation/OpenRV) - Open-source version of RV, a digital review tool for film, TV, and games.
* [Shutterencoder](https://www.shutterencoder.com/) is one of the best video converter software, it handles images and audio too!
* [Pitivi](https://www.pitivi.org/) - Beautiful and powerful video editor based on GStreamer Editing Services.
* [qctools](http://bavc.github.io/qctools/) - A free and open-source software tool that helps users analyze and understand their digitized video files through the use of audiovisual analytics and filtering.
* [Shotcut](https://www.shotcutapp.com/) - A free, open-source, cross-platform video editor.
* [tlRender](https://github.com/darbyjohnston/tlRender) - timeline render, is an early stage project for rendering editorial timelines.
* [UltraGrid](https://github.com/CESNET/UltraGrid) - UltraGrid low-latency audio and video network transmission system.
* [xSTUDIO](https://www.dneg.com/xstudio/) - Image playback and review for the filmmaking community.

### UV/Unwrap library

* [Thekla atlas](https://github.com/Thekla/thekla_atlas) | This tool performs mesh segmentation, surface parameterization, and chart packing.
* [xatlas](https://github.com/jpcy/xatlas) | Fork from [theakla atlas](https://github.com/Thekla/thekla_atlas), it's a library to generate a UV for -example- lightmap uv.

### Tools

*A set of small tools, DCC addons, python library... to complete or add features on DCC software.*

* [Capsule](https://github.com/Takanu/Capsule) - Blender addon to export, manage and automate to share between Blender and Unreal/Unity or other real-time engine. 
* [Genetic Drawing](https://github.com/anopara/genetic-drawing) - Python library to generate a stylized rendering from an image.
* [Glsl Texture](https://github.com/patriciogonzalezvivo/glslTexture) - Create textures from Glsl fragment shaders on Blender (2.8)
* [OD CopyPasteExternal](https://github.com/heimlich1024/OD_CopyPasteExternal) - Tool to easily copy/paste a geometry across 3D application like Blender <> 3DS Max <> Maya <> ... <> and more.
* [Prisma](https://github.com/patriciogonzalezvivo/prisma) - Computational photography pipeline tool that performs multiple inferences (masks, depth, motionvectors) from any image or video.
* [UE4 Env. project](https://github.com/UE4-OceanProject/Environment-Project) - An Environment Simulation project for Unreal Engine 4.
* [LYNX](https://github.com/LucaScheller/VFX-LYNX) - Free & OpenSource VFX Pipeline Tools.
* [qLib](https://github.com/qLab/qLib) - A procedural asset library for SideFX Houdini.
* [SideFX Labs](https://github.com/sideeffects/SideFXLabs) - A completely free, open-source toolset geared towards assisting Houdini users with a variety of tasks commonly used for digital content creation.
* [trigger](https://github.com/masqu3rad3/trigger) - Operational code-driven rigging tool for Autodesk Maya.
* [xComp](https://github.com/gugenstudio/xComp) - Image Render comparing.

### Low-code platforms

* [Appsmith](https://www.appsmith.com/) - To build dashboards quickly.
* [Budibase](https://budibase.com/) - To build simple business apps.
* [Rowy](https://rowy.io/) - To build tables quickly.

### Writing

* [Ink](https://github.com/inkle/ink) - open-source scripting language for writing interactive narratives.

## Libraries

### File path

* [Clique](https://gitlab.com/4degrees/clique) - Another Python module for file sequence parsing and formatting.
* [Fileseq](https://github.com/sqlboy/fileseq) - Frame ranges and file sequences parsing.
* [gofileseq](https://github.com/justinfx/gofileseq) - A Golang port of the library above.
* [Lucidity](http://lucidity.readthedocs.io/en/latest/) - String/filepath templates system inspired by SGTK's template mechanisms.
* [pyseq](https://github.com/rsgalloway/pyseq) - Another Python module for file sequence parsing and serialization.
* [fls](https://github.com/forticheprod/fls) - A Rust command line tool and library to list and pack frame sequences

### UI

* [aframe-vartiste-toolkit](https://www.npmjs.com/package/aframe-vartiste-toolkit) - WebXR/VR UI components toolkit (that the VR drawing app [VArtiste](https://vartiste.xyz/) is built upon.)
* [NiceGUI](https://nicegui.io/) - Create web-based user interfaces with Python. Both native and in the browser.
* [NodeGraphQt](https://github.com/jchanvfx/NodeGraphQt) - Node graph for Qt.
* [Nodz](https://github.com/LeGoffLoic/Nodz) - Node generator for Qt.
* [Qt.py](https://github.com/mottosso/Qt.py) - Qt versions abstraction.
* [QtWebengine](https://github.com/qt/qtwebengine) - Render web content in Qt.
* [Riffle](https://gitlab.com/4degrees/riffle) - A filesystem browser for PySide supporting sequences grouping.
* [SceneGraph](https://github.com/mfessenden/SceneGraph) - Ui for scene graph.
* [Thonside](https://github.com/col-one/thonside) - Python console for Qt apps.

### CG Software API

* [CGCmake](https://github.com/chadmv/cgcmake) - CMake modules for CG apps.
* [Cortex](https://github.com/ImageEngine/cortex) - Libraries for VFX software development.
* [Cross3D](https://github.com/blurstudio/cross3d) - Scene and node management abstraction.
* [ExoCortex for Max 2018](https://github.com/unit-image/ExocortexCrate) - ExoCortex ported to Max 2018.
* [mGui](https://github.com/theodox/mGui) - Portable pure-python GUI library for Maya.
* [minq](https://github.com/theodox/minq) - Maya query language for speeding up common scene operations.
* [NXT](https://nxt-dev.github.io/) - A layered code compositing application.
* [Photoshop Python API](https://github.com/loonghao/photoshop-python-api) - Python API for Photoshop.
* [Py3dsMax](https://github.com/blurstudio/Py3dsMax) - 3dsMax API in Python.
* [PyMEL](https://github.com/LumaPictures/pymel) - Python in Maya Done Right.
* [Pymiere](https://github.com/qmasingarbe/pymiere) - Python API for Premiere Pro.
* [PyTVPaint](https://github.com/brunchstudio/pytvpaint) - Python scripting for TVPaint.
* [OpenFX](https://github.com/ofxa/openfx) - Image processing plug-in standard.

### Geometry

* [BlenderGIS](https://github.com/domlysz/BlenderGIS) - Geo data importer.
* [CGAL](https://www.cgal.org/) - A software project that provides easy access to efficient and reliable geometric algorithms in the form of a C++ library.
* [CvWrap](https://github.com/chadmv/cvwrap) - Fast Maya wrap deformer.
* [Dem Bones](https://www.ea.com/seed/news/open-source-dem-bones) - A library for skinning decomposition.
* [Easy3D](https://github.com/LiangliangNan/Easy3D) - A lightweight, easy-to-use, and efficient C++ library for processing and rendering 3D data .
* [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page) - A C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms.
* [Embree](https://www.embree.org/) - A collection of high-performance ray tracing kernels that help graphics application engineers improve the performance of their photorealistic rendering application.
* [Geometry Central](https://geometry-central.net/) - A modern C++ library of data structures and algorithms for geometry processing, with a particular focus on surface meshes.
* [Optimesh](https://github.com/nschloe/optimesh) - Python library to optimize a triangular mesh and remesh it with various algorithms. 
* [libigl](https://libigl.github.io/) - A simple C++ geometry processing library.
* [MakeHuman](http://www.makehumancommunity.org/) - Parametric human character modeling.
* [Open3D](http://www.open3d.org/) - A Modern Library for 3D Data Processing.
* [OpenSubdiv](http://graphics.pixar.com/opensubdiv/docs/intro.html) - A set of open-source libraries that implement high-performance subdivision surface evaluation on massively parallel CPU and GPU architectures.
* [Partio](https://www.disneyanimation.com/technology/partio.html) - A unified interface that makes it easier to load, save, and manipulate particle files.
* [PCL](https://pointclouds.org/) - A standalone, large scale, open project for 2D/3D image and point cloud processing.
* [Polygon Mesh Processing Library](https://www.pmp-library.org/) - A modern C++ open-source library for processing and visualizing polygon surface meshes.
* [QHull](https://github.com/qhull/qhull/wiki) - Convex hull generator.
* [Rigify](https://github.com/LesFeesSpeciales/rigify) - Auto-rigging Addon for Blender.
* [Simplex](https://github.com/blurstudio/Simplex) - Blendshape Solver.
* [SOFA](https://www.sofa-framework.org/) - An efficient framework dedicated to research, prototyping and development of physics-based simulations.
* [Polyscope](https://github.com/nmwsharp/polyscope) - A C++ & Python viewer for 3D data like meshes and point clouds.

#### Remeshing

* [Quadriflow](https://github.com/hjwdzh/QuadriFlow) - Convert a mesh to a quadrangular algorithm.
* [Instant Meshes](https://github.com/wjakob/instant-meshes) - Remeshing software.
* [autoremesher](https://github.com/huxingyi/autoremesher) -  Automatic quad remeshing tool.
* [mmg](https://github.com/MmgTools/mmg) - mmg is an open source software for bidimensional and tridimensional surface and volume remeshing.

### Colors

* [Colour](https://www.colour-science.org/) - An open-source Python package providing a comprehensive number of algorithms and datasets for color science.
* [OpenColorIO](https://opencolorio.org/) ([repo](https://github.com/AcademySoftwareFoundation/OpenColorIO)) - Unified color environment, a complete color management solution geared towards motion picture production with an emphasis on visual effects and computer animation.

### Shaders

* [BRDF Explorer](https://github.com/wdas/brdf) - The Disney BRDF Explorer is an application that allows the development and analysis of bidirectional reflectance distribution functions.
* [OSL](http://opensource.imageworks.com/?p=osl) - Language to manipulate shaders.
* [Ptex](http://ptex.us/) - A texture mapping system developed by Walt Disney Animation Studios for production-quality rendering.
* [SeExpr](https://github.com/wdas/SeExpr) - An embeddable, arithmetic expression language that enables flexible artistic control and customization in creating computer graphics images.
* [MDL](https://github.com/NVIDIA/MDL-SDK) - Material Definition Language SDK.

### Denosing

* [Intel Open Image Denoise](https://www.openimagedenoise.org/) - An open-source library of high-performance, high-quality denoising filters for images rendered with ray tracing.

## File formats

* [ACES](http://www.oscars.org/science-technology/sci-tech-projects/aces) - Color management.
* [Alembic](http://www.alembic.io/) - Animations.
* [Assimp](https://www.assimp.org/) - A portable Open-Source library to import various well-known 3D model formats in a uniform manner.
* [Cryptomatte](https://github.com/Psyop/Cryptomatte) - Accurate object ID mattes.
* [Field3D](https://magnuswrenninge.com/field3d) - An open-source library for storing voxel data.
* [ImageMagick](https://imagemagick.org/index.php) - Use ImageMagick to create, edit, compose, or convert bitmap images.
* [Kiko](https://github.com/Toolchefs/kiko) - DCC-agnostic animation curves storage (works between Maya and Nuke, with more DCCs to come).
* [MaterialX](https://github.com/materialx/MaterialX) - Materials and look-dev.
* [meshio](https://github.com/nschloe/meshio) - Input/output for many mesh formats.
* [OpenCV](https://opencv.org/) - An open-source computer vision and machine learning software library.
* [OpenDCX](http://www.opendcx.org/) ([repo](https://github.com/dreamworksanimation/opendcx)) - C++ extensions for OpenEXR's "deep" file format.
* [OpenEXR](http://www.openexr.com/) ([repo](https://github.com/AcademySoftwareFoundation/openexr)) - exceptional image format for visual effects purposes, pioneered by ILM.
* [OpenEXRid](https://github.com/MercenariesEngineering/openexrid) - Object isolation.
* [OpenImageIO](https://github.com/OpenImageIO/oiio) - A library for reading and writing images in many common and VFX-related formats.
* [OpenTimelineIO](http://opentimeline.io) ([repo](https://github.com/PixarAnimationStudios/OpenTimelineIO)) - Editorial timeline.
* [Raven](https://github.com/jminor/raven) - Experimental OpenTimelineIO Viewer.
* [OpenVDB AX](https://github.com/dneg/openvdb_ax) - Fast expression language for manipulating OpenVDB files.
* [OpenVDB](http://www.openvdb.org/) ([repo](https://github.com/AcademySoftwareFoundation/openvdb)) - Volumetric data.
* [pfstools](http://pfstools.sourceforge.net/) - A set of command line programs for reading, writing, and manipulating high-dynamic range (HDR) images and video frames.
* [texture-synthesis](https://github.com/EmbarkStudios/texture-synthesis) - Example-based texture synthesis written in Rust.
* [OpenAssetIO](https://github.com/OpenAssetIO/OpenAssetIO) - Interoperability standard for tools and content management systems used in media production.

### USD

* [AL_USDMaya](https://github.com/AnimalLogic/AL_USDMaya) - Represent Maya data in Maya and USD data in USD.
* [luma_usd](https://github.com/LumaPictures/luma_usd) -  Plugins for USD.
* [OpenWalter](https://github.com/rodeofx/OpenWalter) - USD Plugins Arnold, Houdini, Katana, Maya and USD.
* [USD Manager](http://www.usdmanager.org/) - Program designed for lightweight browsing, managing, and editing of Universal Scene Description (USD) files.
* [USD Shell Extension for Windows](https://github.com/Activision/USDShellExtension) - a full-featured Windows shell extension for giving the File Explorer support for USD thumbnails, side previews and even exposes certain deep metadata to Windows Search.
* [usd-arnold](https://github.com/LumaPictures/usd-arnold) - USD Schemas and tools for exchanging Arnold shader information between multiple 3rd party packages.
* [usd-noodle](https://github.com/chris-gardner/usd-noodle) - Pretty node graph showing dependencies of a USD file.
* [USD-URI-resolver](https://github.com/LumaPictures/usd-uri-resolver) - A generic, URI based resolver for USD, support custom plugins.
* [USD](http://graphics.pixar.com/usd/docs/index.html) - Scenes.
* [UsdQt](https://github.com/LumaPictures/usd-qt) - Qt components for building custom USD tools.
* [usd-qtpy](https://github.com/BigRoy/usd-qtpy) - Python Qt components for building custom USD tools.

## File transfer
* [rsync](https://github.com/WayneD/rsync) - Open-source utility that provides fast incremental file transfer. It also has useful features for backup and restore operations among many other use cases.
* [rclone](https://github.com/rclone/rclone) - Rsync for cloud storage Google Drive, S3, Dropbox, Backblaze B2, One Drive, Swift, Hubic, Wasabi, Google Cloud Storage, Yandex Files.
* [Tsunami](https://sourceforge.net/projects/tsunami-udp/) - High-speed file transfer protocol using UDP and TCP for high-speed long-distance networks.
* [UDT](https://udt.sourceforge.io/) - Reliable UDP based application level data transport protocol for distributed data intensive applications over wide area high-speed networks.
* [WDT](https://github.com/facebookarchive/wdt) -  Warp speed Data Transfer (WDT) is an embeddedable library (and command line tool) aiming to transfer data between 2 systems as fast as possible over multiple TCP paths..

## Job schedulers

* [CGRU](http://cgru.info/) is a CG tools pack that includes AFANASY, a free open-source render farm manager.
* [Coalition](http://coalition.readthedocs.io/en/latest/) from Mercenaries Engineering (developers of Guerilla Render).
* [Flamenco](https://flamenco.blender.org/) from the Blender Foundation.
* [OpenCue](https://opencue.io) ([repo](https://github.com/AcademySoftwareFoundation/OpenCue)) An open-source render management system from Sony Imageworks.
* [Pandora](https://prism-pipeline.com/pandora/) Open-Source Renderfarm-Manager.
* [Plow](https://github.com/chadmv/plow) by Chad Vernon.

## Package managers

* [bleeding-rez](https://github.com/mottosso/bleeding-rez) - a very active Rez fork with improved isolation, Windows support, and Python 2+3 support.
* [conda](https://github.com/conda/conda)
* [Ecosystem](https://github.com/PeregrineLabs/Ecosystem)
* [mamba](https://github.com/mamba-org/mamba) - a faster drop-in replacement for "conda".
* [qip](https://github.com/themill/qip) - Quarantined Installer for Python.
* [Rez Packages](https://github.com/predat/rez-packages)
* [Rez](https://github.com/nerdvegas/rez)
* [wiz](https://github.com/themill/wiz)

### Environment Manager

* [Allzpark](https://github.com/mottosso/allzpark) Based on Rez manager, [Allzpark](https://allzpark.com/) can manage
 your software to give a specific software, really useful with the old project.

## Asset managers

* [Avalon](https://getavalon.github.io)
* [Ayon](https://ynput.io/)
* [Damas](http://damas-software.org/)
* [Kabaret](https://www.kabaretstudio.com/)
* [Plex](https://github.com/richteralexander/plex)
* [Prism](https://prism-pipeline.com/)
* [TACTIC-Handler](https://github.com/listyque/TACTIC-Handler)
* [Tik Manager](https://tik-manager.com) - Artist-friendly asset and pipeline manager.

## Production managers

* [Kitsu](https://kitsu.cg-wire.com) - For small to mid-size studios.
* [Ramses](https://github.com/RxLaboratory/Ramses) - Asset Management System for motion picture production (by [Rainbox Laboratory](https://rainboxlab.org)).
* [Stalker](https://github.com/eoyilmaz/stalker) - Open Source Production Asset Management (ProdAM) Library designed specifically for Animation and VFX Studios.

## Content validation

* [Pyblish](http://pyblish.com/) - A Python framework that brings test-driven development to visual effects and
 triple-A game creation.
  * [Blender Pyblish](https://github.com/jasperges/pyblish-blender) - Blender Addon to integrate the Pyblish framework 

## Docker images

* [Animal Logic's USD Docker](https://github.com/AnimalLogic/docker-usd) - A set of docker build scripts that will download all the Open Source packages required to build Pixar's Universal Scene Description, as well as USD itself
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
* [RIFE for Nuke](https://github.com/rafaelperez/RIFE-for-Nuke) - Real-Time Intermediate Flow Estimation for Video Frame Interpolation (ie machine learning for framerate upscaling) for Nuke.
* [Wiretap](https://github.com/predat/wiretap) - Manage Flame Wiretap database

## IDE

### PyCharm

* [MayaCharm](https://github.com/cmcpasserby/MayaCharm) - Run and edit Maya scripts directly from PyCharm
* [USD](https://github.com/justint/usd-idea) - Plug-in for USD

### SublimeText

* [MariSublime](https://github.com/cg-cnu/marisublime) - Run and edit Mari scripts directly from SublimeText
* [MayaSublime](https://github.com/justinfx/MayaSublime) - Run and edit Maya scripts directly from SublimeText
* [NukeToolsSt](https://packagecontrol.io/packages/NukeToolsST) - A Sublime Text package to send Python or BlinkScript code inside Nuke.
* [VEX](https://github.com/teared/VEX) - Houdini add-on for Sublime Text

### vim

* [nuke.vim](https://github.com/heavyimage/nuke.vim) - Run and edit Nuke scripts directly from vim

### VSCode

* [blender_vscode](https://github.com/JacquesLucke/blender_vscode) - Visual Studio Code extension for Blender development.
* [Blink Script (Nuke) Language Syntax](https://marketplace.visualstudio.com/items?itemName=melmass.blink) ([repo](https://github.com/melMass/vscode-blink.git)) - for syntax highlighting support.
* [MayaCode](https://marketplace.visualstudio.com/items?itemName=saviof.mayacode) ([repo](https://github.com/artbycrunk/vscode-maya)) - Maya syntax highlighting support, along with autocomplete commands and send code to maya via command port.
* [MayaPort](https://marketplace.visualstudio.com/items?itemName=JonMacey.mayaport) ([repo](https://github.com/NCCA/mayaport)) - Run Maya code from VSCode.
* [MEL Language Syntax](https://github.com/sator-imaging/Visual-Studio-Code-MEL-Language.git) ([repo](https://github.com/sator-imaging/Visual-Studio-Code-MEL-Language.git)) - for syntax highlighting support.
* [Nuke Tools](https://marketplace.visualstudio.com/items?itemName=virgilsisoe.nuke-tools) - Nuke tools to help the development process inside Visual Studio Code.
* [Pixar USD ASCII Language Syntax](https://marketplace.visualstudio.com/items?itemName=AnimalLogic.vscode-usda-syntax) ([repo](https://github.com/AnimalLogic/AL_usd_vscode_extension)) - for syntax highlighting support, courtesy of the folks at Animal Logic.
* [SendtoMaya](https://marketplace.visualstudio.com/items?itemName=ivancheung7.sendtomaya) - Alternative to MayaPort, serving the same purpose.
* [VEX Language Syntax](https://marketplace.visualstudio.com/items?itemName=melmass.vex) ([repo](https://github.com/melMass/vscode-vex.git)) - for syntax highlighting support.

### VSCodium

* [Nuke Tools](https://open-vsx.org/extension/virgilsisoe/nuke-tools) - Nuke tools to help the development process inside Visual Studio Code.

### vscode.dev

* [DCC WebSocket](https://marketplace.visualstudio.com/items?itemName=virgilsisoe.dcc-websocket) - A WebSocket client to send code from [vscode.dev](https://vscode.dev/) web browser text editor to a DCC application.

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
* [The Pipeline Conference](https://thepipelineconference.com)
* [Pipeline Developer Forum](https://pipedev.org)
* [StudioSysAdmins](http://studiosysadmins.com)
* [Tech-artists.org](http://tech-artists.org)

## Resources / Tutorials

* [cgwiki](http://www.tokeru.com/cgwiki/)
* [Beginning Python For Maya](https://zurbrigg.teachable.com/p/python-3-for-maya-vol-1)
* [Blue Sky Studios Tech Blog](https://medium.com/blue-sky-tech-blog)
* [Digital Video Introduction](https://github.com/leandromoreira/digital_video_introduction)
* [Example of Python scripts for 3D Studio Max, Maya and Blender](https://github.com/p4vv37/3D_Software_and_Python/)
* [Les Fées Spéciales Studio Tech Blog](http://lacuisine.tech/)
* [Pipeline Patterns](http://www.pipelinepatterns.com/)
* [Unit Testing in Maya](http://www.chadvernon.com/blog/maya/unit-testing-in-maya/)
* [VFX good night reading](https://github.com/jtomori/vfx_good_night_reading/) - Curated collection of good reading about VFX and CG.

## Free music for showreel

* [Music For Vlogs](https://soundcloud.com/freemusicforvlogs)
* [Wowa](https://www.wowa.me/)

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/frankrousseau"><img src="https://avatars1.githubusercontent.com/u/1336623?v=4?s=100" width="100px;" alt="Frank Rousseau"/><br /><sub><b>Frank Rousseau</b></sub></a><br /><a href="#content-frankrousseau" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/loonghao"><img src="https://avatars1.githubusercontent.com/u/13111745?v=4?s=100" width="100px;" alt="Hal"/><br /><sub><b>Hal</b></sub></a><br /><a href="#content-loonghao" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://darkvertex.com"><img src="https://avatars0.githubusercontent.com/u/941331?v=4?s=100" width="100px;" alt="Alan Fregtman"/><br /><sub><b>Alan Fregtman</b></sub></a><br /><a href="#content-darkvertex" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/notawhalevfx"><img src="https://avatars2.githubusercontent.com/u/45572972?v=4?s=100" width="100px;" alt="Nikita Musatov"/><br /><sub><b>Nikita Musatov</b></sub></a><br /><a href="#content-notawhalevfx" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://sreenivas.dev"><img src="https://avatars0.githubusercontent.com/u/2767425?v=4?s=100" width="100px;" alt="sreenivas alapati"/><br /><sub><b>sreenivas alapati</b></sub></a><br /><a href="#content-cg-cnu" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://artstation.com/artist/stilobique"><img src="https://avatars0.githubusercontent.com/u/3066684?v=4?s=100" width="100px;" alt="Stilobique"/><br /><sub><b>Stilobique</b></sub></a><br /><a href="#content-stilobique" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/bob-white"><img src="https://avatars0.githubusercontent.com/u/7028615?v=4?s=100" width="100px;" alt="bob-white"/><br /><sub><b>bob-white</b></sub></a><br /><a href="#content-bob-white" title="Content">🖋</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://www.nothing-is-3d.com/"><img src="https://avatars0.githubusercontent.com/u/3873421?v=4?s=100" width="100px;" alt="Vincent Lamy"/><br /><sub><b>Vincent Lamy</b></sub></a><br /><a href="#content-Vinc3r" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://blog.theodox.com"><img src="https://avatars3.githubusercontent.com/u/4056600?v=4?s=100" width="100px;" alt="Steve Theodore"/><br /><sub><b>Steve Theodore</b></sub></a><br /><a href="#content-theodox" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.cube-creative.com/"><img src="https://avatars2.githubusercontent.com/u/26791257?v=4?s=100" width="100px;" alt="Cube Creative"/><br /><sub><b>Cube Creative</b></sub></a><br /><a href="#content-developer-cube-creative" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.bumpybox.com"><img src="https://avatars0.githubusercontent.com/u/1860085?v=4?s=100" width="100px;" alt="Toke Jepsen"/><br /><sub><b>Toke Jepsen</b></sub></a><br /><a href="#content-tokejepsen" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://santoshk.dev"><img src="https://avatars3.githubusercontent.com/u/1515991?v=4?s=100" width="100px;" alt="Santosh Kumar"/><br /><sub><b>Santosh Kumar</b></sub></a><br /><a href="#content-santosh" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/listyque"><img src="https://avatars2.githubusercontent.com/u/13370598?v=4?s=100" width="100px;" alt="Alex Miarsky"/><br /><sub><b>Alex Miarsky</b></sub></a><br /><a href="#content-listyque" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://justintennant.me"><img src="https://avatars2.githubusercontent.com/u/7485210?v=4?s=100" width="100px;" alt="Justin Tennant"/><br /><sub><b>Justin Tennant</b></sub></a><br /><a href="#content-justint" title="Content">🖋</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://jtomori.github.io"><img src="https://avatars0.githubusercontent.com/u/22801191?v=4?s=100" width="100px;" alt="Juraj Tomori"/><br /><sub><b>Juraj Tomori</b></sub></a><br /><a href="#content-jtomori" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://hellozee.dev"><img src="https://avatars1.githubusercontent.com/u/12135951?v=4?s=100" width="100px;" alt="Kuntal Majumder"/><br /><sub><b>Kuntal Majumder</b></sub></a><br /><a href="#content-hellozee" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/jfpanisset"><img src="https://avatars0.githubusercontent.com/u/32653482?v=4?s=100" width="100px;" alt="Jean-Francois Panisset"/><br /><sub><b>Jean-Francois Panisset</b></sub></a><br /><a href="#content-jfpanisset" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.heavyimage.com"><img src="https://avatars0.githubusercontent.com/u/7820487?v=4?s=100" width="100px;" alt="Jesse Spielman"/><br /><sub><b>Jesse Spielman</b></sub></a><br /><a href="#content-heavyimage" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://www.corentin-charron.com"><img src="https://avatars2.githubusercontent.com/u/4436347?v=4?s=100" width="100px;" alt="Corentin"/><br /><sub><b>Corentin</b></sub></a><br /><a href="#content-corentincharron" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://www.saviof.com"><img src="https://avatars0.githubusercontent.com/u/1092099?v=4?s=100" width="100px;" alt="Savio Fernandes"/><br /><sub><b>Savio Fernandes</b></sub></a><br /><a href="#content-artbycrunk" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://in.linkedin.com/in/anvith-shivakumara"><img src="https://avatars3.githubusercontent.com/u/5442547?v=4?s=100" width="100px;" alt="Anvith Shivakumara"/><br /><sub><b>Anvith Shivakumara</b></sub></a><br /><a href="#content-anvth" title="Content">🖋</a></td>
    </tr>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/aboellinger"><img src="https://avatars0.githubusercontent.com/u/5718135?v=4?s=100" width="100px;" alt="Antoine Boellinger"/><br /><sub><b>Antoine Boellinger</b></sub></a><br /><a href="#content-aboellinger" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/mathbou"><img src="https://avatars1.githubusercontent.com/u/13415583?v=4?s=100" width="100px;" alt="Mathieu Bouzard"/><br /><sub><b>Mathieu Bouzard</b></sub></a><br /><a href="#content-mathbou" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://pype.club"><img src="https://avatars.githubusercontent.com/u/3333008?v=4?s=100" width="100px;" alt="Milan Kolar"/><br /><sub><b>Milan Kolar</b></sub></a><br /><a href="#content-mkolar" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/mwestphal"><img src="https://avatars.githubusercontent.com/u/3129530?v=4?s=100" width="100px;" alt="mwestphal"/><br /><sub><b>mwestphal</b></sub></a><br /><a href="#content-mwestphal" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="http://eoyilmaz.blogspot.com"><img src="https://avatars.githubusercontent.com/u/1786804?v=4?s=100" width="100px;" alt="Erkan Ozgur Yilmaz"/><br /><sub><b>Erkan Ozgur Yilmaz</b></sub></a><br /><a href="#content-eoyilmaz" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://mcoliver.com/"><img src="https://avatars.githubusercontent.com/u/622057?v=4?s=100" width="100px;" alt="Michael Oliver"/><br /><sub><b>Michael Oliver</b></sub></a><br /><a href="#content-mcoliver" title="Content">🖋</a></td>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/potahto"><img src="https://avatars.githubusercontent.com/u/8496837?v=4?s=100" width="100px;" alt="potahto"/><br /><sub><b>potahto</b></sub></a><br /><a href="#content-potahto" title="Content">🖋</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

*[DCC]: *Data Content Creation* software. 
