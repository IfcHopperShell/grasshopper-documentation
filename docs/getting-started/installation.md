---
sidebar_position: 1
title: Installation
sidebar_label: Installation
---

This page will guide you through the installation of the IfcHoppeShell plugin for Rhino/Grasshopper.

## Prerequisites
Before you install the actual plugin, you need to have:
- the Windows operating system;
- Rhino 8 or greater (grasshopper comes preinstalled with Rhino);
- a valid python 3.9 Rhino environment: in Rhino run the `ScriptEditor` command. If it's the first time you use it, let the python environment to initialize. A `.rhinocode` folder will be created in your user folder (like `C:\Users\hopperuser\.rhinocode\`) and an instance of pyhon 3.9, specific to Rhino, will be installed.

:::info
Note that Rhino uses its own python installation, so it doesn't matter if you already have some python version installed in your system.
:::

:::tip
If you are under a company network, you may need to ask your IT department to let you computer reach `https://pypi.org/`. Also, if a proxy is present you may need to edit the `pip.ini` config file in the `.rhinocode` folder accordingly.
:::

## Install the ifcopenshell python library
The IfcHopperShell plugin relies on the python library [ifcopenshell](https://docs.ifcopenshell.org/).

To install it in the Rhino python environment:
- open Rhino 8 (or greater);
- Run the `ScriptEditor` command;
- in the opened window top menu click on `Tools > Advanced > Open Python 3 Shell`;
- in the opened shell, type `pip install ifcopenshell` and wait for it to complete the installation;
- you can now close both the shell and the ScriptEditor.

## Install the IfcHopperShell grasshopper plugin
- open Rhino 8 (or greater);
- Run the `PackageManager` command;
- In the search bar type **IfcHopperShell**;
- Click `Install` and wait.
- Enjoy!

## How to use
Go to the next section of the docs for instructions on how to use the plugin.