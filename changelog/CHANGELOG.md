# Changelog

## v3.2.0
- Added new State Machine graph and support for Class Component & C# Graph that inherit from MonoBehaviour
- Added new Call Stack window, auto open when breakpoint is hit in playmode allowing for see the execution flows and has ability to highlight node, ping object, and open script.
- Added ability to make connection by single click on the port ( no need to hold down left button )
- Renamed State Graph to Event Graph
- Improved C# Parser
- Improved Code Generation
- Improved Editor
- Fixed most of reported bugs

## v3.1.5
- Added more drag & drop menu items
- Improved Code Generation
- Improved Editor
- Fixed some bugs

## v3.1.4
- Added more option to configure sticky note style
- Added setting for default access modifier for new property by @Miftachul-Huda
- Added unscaled time on NodeTimer by @Miftachul-Huda
- Improved Code Generation
- Improved Editor
- Remove generated script after build by @Miftachul-Huda
- Fixed obselete warnings on unity 6 by @Miftachul-Huda
- Fixed some bugs

## v3.1.3
- Added option to configure node icon in Node Creator Wizard
- Improved C# Parser
- Improved Editor
- Fixed some bugs

## v3.1.2
- Added option to change max displayed recent items in Item Selector
- Added option to hide sticky note title
- Added option to configure summary for function parameters
- Added new configure shortcut to open uNode Editor, Compile C# Graphs, and Compile Runtime Graphs
- Improved Code Generation
- Improved Editor
- Fixed bug summary in variable is not included in c# output
- Fixed reported bugs

## v3.1.1
- Improved C# Parser
- Improved Editor
- Fixed Cannot add override property from inherited c# graph
- Fixed UI bug when editing list or array
- Fixed UI bug when Inspecting node
- Fixed Cut command is not working
- Fixed Graph Converter is not working
- Fixed sometime undo is not working
- Fixed some bugs

## v3.1.0
- Improved Code Generation
- Improved Editor
- Improved Graph Component, prevent editing prefab instance but allow to override the variables this will ensure the Graph Component is using same graph with the original prefab.
- Changes serialization behaviour, the graph will now serialized by Unity instead of Odin Serializer resulting in more fast editing graph, smaller file size, and version control friendly. ( This is breaking changes, make sure to backup your projects )
- Fixed serialization error in build because of link.xml is not included on IL2CPP backend
- Fixed some bugs

## v3.0.8
- Improved Editor
- Fixed some bugs

## v3.0.7
- Added default value support for parameters
- Added Graph Inspector window, useful if needed to see both node properties and game object properties on the screen in the same time
- Update Roslyn to latest version
- Improved c# parser
- Improved Editor
- Fixed some bugs

## v3.0.6
- Added Bookmarks feature allowing capture the position and zoom level of the canvas and the active tab you were viewing for later jump it after created the bookmark
- Added `remove unnecessary code` preference to remove unnecessary code for better readable code. can be enable from uNode preference > Code Generation > Analize Script > Remove Unused Code
- Improved Code Generation
- Improved Editor
- Improved Global Search
- Fixed some bugs

## v3.0.5
- Added Node Creator Wizard
- Added Constructor Initializers, psudo Default Constructors and Relevant search kind by @S2NX7
- Added Surround menu commands by @S2NX7
- Added disable right click to move the graph canvas in preference
- Improved Code Generation
- Improved Editor
- Improved AutoFix error nodes
- Removed dependency to `com.unity.ugui`
- Fixed some bugs

## v3.0.4
- added ability to copy paste value in reorderable list
- added ability to view all listeners in global events
- added ability to find all reference for global events
- improved c# parser
- improved code generation
- improved editor
- fixed most of reported bugs

## v3.0.3
- added description for some nodes
- added `Change All C# Type to Graph Type` menu to change all reference of CLR type to uNode graph type useful for some cases like after parsing c# script
- improved expression node, fixed some bug and more syntax is supported
- improved c# parser
- improved code generation
- improved editor
- fixed some node is not displaying correct icon
- fixed error on live editing LinkedMacro
- fixed some bugs

## v3.0.2
- added support to assign interface value
- added promote to local variable for output port context menu
- added promote to parameter context menu
- added ability to find all references for global events
- improved c# parser
- improved code generation
- improved editor
- fixed some warning in Unity 6
- fixed some bugs

## v3.0.1
- Added new Light theme
- Added support for add input port for transition
- Improved C# Parser
- Improved Editor
- Fixed most of reported bugs

## v3.0.0
- First release