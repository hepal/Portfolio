# Automated BIM Energy Performance & U-Value Calculator via Revit API

A custom Autodesk Revit add-in that automates the extraction and analysis of building energy performance data directly from BIM models, eliminating manual takeoffs and calculation errors in thermal performance reporting.

## Overview

This tool plugs directly into Revit's live model data via the **Revit API** to identify and analyze the materials of exterior walls, openings, and floors. It automatically calculates the thermal conductivity of composite building assemblies and generates ready-to-submit energy performance certificates and thermal transmittance (**U-value**) reports — turning a process that traditionally takes hours of manual measurement and spreadsheet work into a single automated workflow.

**Business value:** faster, more accurate energy compliance documentation, reduced manual data entry, and consistent, audit-ready thermal performance reports for building projects.

## Preview

![Wall Area Analysis Output Sheet](./image_original.png)

*Auto-generated wall area analysis sheet extracted directly from the Revit model, ready for certification submission.*

![Thermal Transmittance (U-value) Schedule](./image_original2.png)

*Automatically generated thermal performance schedule detailing composite material layers, thickness, and calculated U-values for each building element.*

## Key Features & Problem Solving

- **Automated BIM Data Extraction** — reads exterior wall, opening, and floor data directly from the live Revit model via the Revit API, removing the need for manual measurement or re-entry.
- **Composite Material Analysis** — identifies multi-layer wall, floor, and opening assemblies and systematically calculates the thermal conductivity of each composite material.
- **Automated U-value Calculation** — computes thermal transmittance (U-value) for every analyzed building element according to standard methodology.
- **Auto-Generated Reports & Sheets** — produces complete energy performance certificates and U-value schedules as native Revit sheets, formatted and ready for submission.
- **Accuracy & Efficiency Gains** — significantly reduces manual data entry effort while ensuring highly accurate, repeatable environmental data analysis across projects.

## Tech Stack

- C#
- .NET Framework
- Autodesk Revit API

## Role

Lead Developer — responsible for full software architecture, development, and implementation.
