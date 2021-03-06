# NUI overview

This overview provides an introduction to NUI and the DALi engine.

+ NUI  - Natural User Interface
+ DALi - Dynamic Animation Library

NUI is a C# interface to the original DALi graphics library which was written in C++.

## NUI 

NUI is a cross platform library for creating applications with rich GUI. These applications are run on a
range of Tizen devices such as TV's and wearables. NUI is built on a multi-threaded architecture enabling
realistic smooth animations. In addition a range of optimisation techniques are utilised to obtain low CPU and GPU
usage, further increasing graphics performance.

NUI enables developers to quickly create Rich UI applications with realistic effects and animations such as:

 + Image & Video galleries
 + Music players
 + Games
 + Maps
 + Homescreens / launch pads
 + Advanced watch faces for wearable devices

## NUI features

 + Maintains a hierarchical 3D scene graph consisting of parent and child nodes
 + Creates images & text
 + Provides Layers to aid in 2D UI layout
 + Automatic background loading of resources
 + Easy to use Animation framework which hides the complexity of the underlying 3D Math.
 + Provides keyboard / touch / mouse handling

## NUI Key concepts

Scene graph: Tree data structure, consisting of a collection of nodes.

Nodes:       Image, text, buttons etc.

Window:      Top level node of the scene graph, used for displaying a tree of Views.

View:        Primary object for interaction. Views are effectively nodes that receive input (such as touch events),
             and act as a container for drawable elements and other views. A NUI application uses a hierarchy of view
             objects to position visible content.

Layer:       Differant levels within an image. Layers provide a mechanism for overlaying groups of views on top of each other.

### Last updated - May 2017



