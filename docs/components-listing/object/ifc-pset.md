---
sidebar_position: 12
title: Ifc Pset
sidebar_label: Ifc Pset
---

Create a Pset and assign it to an IFC Object.

<p align="center">
  <img src="https://ifchoppershell.github.io/grasshopper-documentation/img/ifc_pset.PNG" />
</p>

## Input
1. **Model***: the IfcOpenShell model.

2. **Name**: the name of the pset (default is "Hopper Pset").

3. **Object Id***: the object (or list of objects) id to assign the pset to.

4. **Keyes**: the keys as list (or tree, one branch per object id).

5. **Values**: the values as list (or tree, one branch per object id).

\* Required

## Output
1. **Model**: the IfcOpenShell model.

2. **Pset Id**: the pset id.
