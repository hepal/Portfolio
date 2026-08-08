# Web-Based 3D Data Center Infrastructure Management (DCIM) Digital Twin

The core 3D visualization and frontend application for a web-based Data Center Infrastructure Management (DCIM) platform, letting operators monitor, manage, and track server racks and IT assets as an interactive digital twin directly in the browser.

## Overview

This platform gives data center operators a fully interactive 3D digital twin of their physical infrastructure, accessible from any web browser — no native client required. My focus was the technical implementation of the 3D environment itself and the real-time, bidirectional synchronization between the 3D WebGL canvas and the 2D web UI layer (UI/UX design was provided separately by the design team).

**Business value:** intuitive, real-time visibility into rack and IT asset status without leaving the browser, faster identification and tracking of infrastructure changes, and a unified 3D/2D interface that reduces operator training time.

## Preview

![Interactive 3D data center digital twin with live rack detail panels and change/deployment tracking](./image_original.png)

*Interactive 3D rack view with live asset detail panels, IT asset information, and change/deployment history — all synchronized with the 2D UI in real time.*

## Key Features & Problem Solving

- **Real-Time 3D Digital Twin** — a fully interactive, browser-based 3D representation of physical server racks and IT assets, built with Three.js/WebGL.
- **3D ↔ 2D UI Synchronization** — bidirectional, real-time sync between the WebGL 3D canvas and the React-based 2D UI, so selections, filters, and updates stay consistent across both views.
- **Interactive Asset Inspection** — clicking racks or assets in the 3D scene surfaces detailed IT asset information (model, specs, position, status) in context-aware panels.
- **Change & Deployment Tracking** — a dedicated panel surfaces asset change/deployment history (work type, date, status, contents) tied directly to the visualized assets.
- **Section & Rack Navigation** — a structured section/rack tree lets operators quickly locate and drill into specific racks within large facilities.
- **API-Integrated Live Data** — the 3D environment is driven by live backend data via API integration, keeping the digital twin in sync with real infrastructure state.

## Tech Stack

- Three.js
- React
- WebGL
- Front-End Development
- API Integration

## Role

3D Web & Frontend Developer.
