# SemiBlock Flowchart

The SemiBlock Flowchart editor is a visual design tool for creating classic flowcharts using an interactive SVG canvas. It is embedded in the SemiBlock platform and helps students and educators diagram algorithms, control flows, data processing, and decision logic.

## Key Features

- **7 built-in shapes** in a left Palette: Start/End (ellipse), Process (rounded rect), Decision (diamond), Input/Output (parallelograms), Point (connector dot), and Arrow.
- **Drag-and-snap editing**: Shapes snap to a 20 px grid. Drag to reposition; live arrow connections update.
- **Arrow connections**: Select the Arrow tool, then click two connection points (4 cardinal points on most shapes, 1 on Point) to link them. Labels on arrows are editable; arrowheads are omitted when targeting a Point.
- **Live Properties panel** (collapsible, right side): Edit label text, font size (10-48 px), width/height (snapped), color (16 swatches), and for arrows a text offset slider.
- **Code View**: Toggle to a Monaco JSON editor showing the exact `{ shapes: [...], arrows: [...] }` model. Edit and "Update Flowchart" to round-trip back to the visual Builder.
- **Persistence & Projects**: Auto-saves to browser localStorage. Use the toolbar to Save (syncs to your SemiBlock account), Open previous projects, Copy URL for sharing, or start New.
- **Export**: Print / Export PNG (with background matching current theme).
- **Undo/Redo, Zoom, Theme**: Full undo stack (via custom event), zoom controls, light/dark mode persisted in localStorage.
- **Integration**: Built with React + MUI + Vite + Monaco; deployed under `/flowchart-build/` in the platform. The flowchart logo appears in the app bar.

## How It Fits in SemiBlock

Flowchart complements the Blockly-based visual programming tools (Java, JVM, 4WD, etc.) by providing a higher-level, language-agnostic way to plan logic before or alongside coding. Use it for requirements, algorithm design, debugging discussions, or documentation.

See the [Getting Started](getting-started.md) guide and explore the live editor inside your SemiBlock workspace.