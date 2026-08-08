# SketchUp Spatial Data Pipeline & IndoorGML Modeler

A SketchUp Ruby plugin that converts CAD/CityGML data into IndoorGML, bridging desktop CAD modeling with web-based indoor spatial systems through a single validated authoring pipeline.

## Overview

IndoorGML is the OGC standard for indoor spatial data, but authoring and validating it typically requires specialized GIS tooling disconnected from how architectural/CAD data is actually modeled. This plugin builds the entire pipeline directly inside SketchUp: it imports CAD (DXF) and CityGML source data, provides a custom GUI to edit every IndoorGML spatial element, validates the result for data integrity, and exports standards-compliant `*.IndoorGML` and InViewer files ready for web consumption.

**Business value:** eliminates the disconnect between CAD authoring and indoor GIS standards, catches data-integrity errors before export via built-in validation, and produces web-ready indoor spatial data without leaving a familiar CAD environment.

## Preview

![SketchUp plugin functional workflow: CAD/CityGML to IndoorGML to Export](./image_original.png)

*End-to-end pipeline: CAD/CityGML source data → IndoorGML conversion → in-SketchUp editing (Cell Space, Topology, POI, Property, Coordinate System, Anchor Node) → Validator → IndoorGML/InViewer export.*

## Media Gallery

| Import & Conversion GUI | Validation Workflow |
|---|---|
| ![IndoorGML plugin conversion dialog in SketchUp](./image_original3.png) | ![IndoorGML validate check and confirm workflow leading to export](./image_original2.png) |
| Custom conversion GUI for importing DXF/CityGML source data and configuring wall, door, window, and material parameters. | Built-in validator checks converted data for integrity, surfaces errors through a dedicated GUI, and confirms before final IndoorGML export. |

## Key Features & Problem Solving

- **CAD-to-IndoorGML Conversion Pipeline** — imports both CAD (DXF) and CityGML source data and converts them into the IndoorGML spatial data model directly within SketchUp.
- **Custom Spatial Editing GUI** — dedicated tools to create and edit Cell Spaces, Topology, POIs, Properties, Coordinate Systems, and Anchor Nodes without leaving the SketchUp environment.
- **Built-In Data Validator** — validates converted spatial data for structural and topological integrity, with error-handling GUIs that guide the user to fix issues before export.
- **Standards-Compliant Export** — exports verified data into `*.IndoorGML` and InViewer formats, ready for consumption by web-based indoor spatial systems.
- **CAD-to-Web Bridge** — seamlessly connects familiar desktop CAD modeling workflows to downstream web-based spatial/GIS platforms.

## Tech Stack

- SketchUp
- Ruby
- Plugin Development
- .NET Framework

## Role

Lead Developer — handled the entire technical architecture and software development.
