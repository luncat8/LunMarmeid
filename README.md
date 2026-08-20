# Diagram & Mermaid Visual Editor

A lightweight web-based visual editor for Mermaid diagrams (especially flowcharts) using a drag-and-drop canvas plus live code editing and preview.

## Features

- **Visual Canvas**
  - Drag-and-drop nodes
  - Create links by dragging from node handles
  - Zoom/pan, grid, snap-to-grid option
  - Multi-select with marquee selection and Ctrl/Cmd+click
  - Node shapes: rectangle, rounded, circle, diamond, stadium

- **Live Mermaid Code**
  - Generates standard Mermaid flowchart code as you edit
  - Edit Mermaid code directly; changes are parsed back to canvas objects

- **Mermaid Preview**
  - Renders the diagram using official Mermaid library

- **Object & Link Properties**
  - Edit node IDs, labels, shapes, sizes, colors, parent relationships
  - Edit link labels, colors, endpoints
  - Search/filter objects by ID/label/type in selection dropdown

- **Import / Export**
  - Save/load objects as JSON (preserves layout, hierarchy, canvas state)
  - Load Mermaid `.mmd` text and apply its layout to the canvas
  - Export:
    - Mermaid code (.mmd)
    - Preview SVG
    - Objects JSON
