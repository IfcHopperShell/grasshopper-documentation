---
sidebar_position: 13
title: Ifc Qto
sidebar_label: Ifc Qto
---

Create a Qto and assign it to an IFC Object.

<p align="center">
  <img src="/img/ifc_qto.png" />
</p>

## Input
1. **Model***: the IfcOpenShell model.

2. **Name**: the name of the qto (default is "Hopper Qto").

3. **Object Id***: the object (or list of objects) id to assign the pset to.

4. **Quantity Type**: a type.

    Can be:
    - "Number"
    - "Count"
    - "Length"
    - "Area"
    - "Volume"
    - "Time"

    (default is "Length").

5. **Keyes**: the keys as list (or tree, one branch per object id).

6. **Values**: the values as list (or tree, one branch per object id).

\* Required

## Output
1. **Model**: the IfcOpenShell model.

2. **Qto Id**: the qto id.