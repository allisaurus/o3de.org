---
description: ' Use the UI Canvas Asset Ref component in Open 3D Engine to associate a UI
  canvas with a component entity in a level. '
title: UI Canvas Asset Ref
---



With the **UI Canvas Asset Ref** component, you can associate a UI canvas with a component entity in a level.

When you set up a UI canvas asset ref component, you can:
+ Select whether to automatically load the UI canvas when the level loads
+ Use Script Canvas that is associated with the UI canvas to reference it using the **UI Canvas Asset Ref** Script Canvas nodes.

Use this component in conjunction with the [**UI Canvas on Mesh**](/docs/user-guide/components/reference/ui/canvas-on-mesh/) component if you want to place a UI canvas on a 3D mesh that a player can interact with.

For more information about how to use the **UI Canvas Asset Ref** component, see [Placing UI Canvases in the 3D World](/docs/user-guide/interactivity/user-interface/editor/placing-canvases-3d/).

## UI Canvas Asset Ref Component Properties 

The **UI Canvas Asset Ref** component has the following properties:

**Canvas pathname**
The relative pathname of the UI canvas asset file.

**Load automatically**
If selected, the canvas is automatically loaded when this component entity is loaded, typically when the level is loaded.
