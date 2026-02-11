---
sidebar_position: 4
title: Ifc Get Mesh
sidebar_label: Ifc Get Mesh
---

Get all geometries of the Model as meshes, with relative colors, ids, psets and qtos.

<p align="center">
  <img src="/img/ifc_get_mesh.png" />
</p>

## Input

1. **Model***: the IfcOpenShell model.

2. **Include**: a list of IFC classes to include in the query (others will be excluded).

3. **Exclude**: A list of IFC classes to exclude from the query (others will be included).

\* required

## Output

1. **Mesh**: the meshes found in the model.

2. **Colors**: the colors assigned to the meshes.

3. **Step Id**: the step id of the related objects.

4. **Pset Id**: the ids of the associated psets.

5. **Qto Id**: the ids of the associated qtos.