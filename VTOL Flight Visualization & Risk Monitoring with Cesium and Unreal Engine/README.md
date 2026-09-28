# VTOL Flight Visualization & Risk Monitoring with Cesium and Unreal Engine

A nationwide 3D monitoring system that visualizes VTOL (Vertical Take-Off and Landing) aircraft flights over South Korea on a real-world 3D map, built with Cesium for Unreal on Unreal Engine, and analyzes and displays potential risk factors along each flight.

## Overview

Operating eVTOL / UAM aircraft over dense urban areas requires operators to understand where a vehicle is, where it has been, and what conditions around it could put the flight at risk — information that is hard to read from 2D maps and raw telemetry tables. This project brings that information into a single 3D view:

1. **Geospatial 3D scene** — Cesium for Unreal streams georeferenced, photorealistic 3D terrain and buildings covering South Korea, so flights are shown against the actual city and mountain context they fly through.
2. **Flight visualization** — each vehicle is placed at its real GPS position and altitude, with its flight path rendered as a 3D trajectory ribbon and live flight details shown in an overlay panel.
3. **Risk analysis & display** — potential risk factors around the flight (e.g. surrounding terrain and structures, weather conditions) are analyzed and surfaced to the operator in the monitoring UI.

**Business value:** operators get an intuitive, real-world 3D picture of VTOL operations across the country, making it easier to monitor flights and spot hazardous situations early instead of piecing them together from separate data sources.

## Preview

![3D Visualization Monitoring — an eVTOL following its GPS flight path over the city, with vehicle details and weather panels](image_original.png)

## Key Features

- **Nationwide 3D Map** — Cesium for Unreal with georeferenced photorealistic 3D tiles, placing flights over real terrain and buildings across South Korea.
- **GPS-Based Flight Rendering** — converts latitude / longitude / altitude into the Unreal world so the aircraft model flies at its true position.
- **3D Flight Path Trajectory** — renders the route as a translucent ribbon in 3D space, making altitude changes and turns visible relative to the surrounding city.
- **Vehicle Detail Panel** — shows the selected vehicle's GPS coordinates, flight speed, and flight altitude.
- **Weather Panel** — displays location, temperature, wind speed, wind direction, and timestamp as flight-condition context.
- **Risk Factor Analysis** — analyzes potential risk factors along the flight and presents them in the monitoring interface, with notifications for the operator.
- **Monitoring UI** — dedicated "3D Visualization Monitoring" layout with a tool sidebar for switching between flight, route, area, and view functions.

## Tech Stack

- Unreal Engine
- UnrealScript
- GIS (Cesium for Unreal, 3D Tiles, WGS84 GPS coordinates → engine world coordinates)

## Role

Main Programmer.
