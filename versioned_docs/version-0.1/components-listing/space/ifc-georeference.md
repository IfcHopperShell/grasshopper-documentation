---
sidebar_position: 8
title: Ifc Georeference
sidebar_label: Ifc Georeference
---

Georeference the Ifc Context.

<p align="center">
  <img src="https://ifchoppershell.github.io/grasshopper-documentation/img/ifc_georeference.PNG" />
</p>

## Input
1. **Model***: the IfcOpenShell model.

2. **Projected CRS**: the EPSG code for the projection (default is 4326; i.e. WGS84).

3. **Eastings**: the longitude of the project (default is 0.0).

4. **Northings**: the latitude of the project origin (default is 0.0).

5. **North Angle**: the angle between the project and world north, counterclockwise is positive (default is 0.0).

6. **Origin Scale**: the scale at the origin (dafault is 1.0).

\* Required

## Output
1. **Model**: the IfcOpenShell model.

2. **Context Id**: the context id.