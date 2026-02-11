---
sidebar_position: 11
title: Ifc Object
sidebar_label: Ifc Object
---

Create an IFC Object.

<p align="center">
  <img src="https://raw.githubusercontent.com/IfcHopperShell/grasshopper-documentation/refs/heads/gh-pages/img/ifc_object.png" />
</p>

## Input
1. **Model***: the IfcOpenShell model.

2. **Name***: a list of names (default is "Hopper Object").

3. **Relating Object Id***: a list of relating object ids, usually the storey, the building etc.

4. **Context Id***: a list of context ids.

5. **Class**: a list of IFC classes (default is "IfcBuildingElementProxy").

6. **Mesh**: a list of meshes that make up the representation of this object.

    Note: a mesh is not required, an object can exist without a geometric reperesentation.

7. **Color**: a list of colors to assign to the objects (if they have a geometric representation).

    Note: if a color is not provided, different software may display the objects with different styling, but it still works.

\* Required

## Output
1. **Model**: the IfcOpenShell model.

2. **Object Id**: the object id.