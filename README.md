# 🛸 PixelForge OS: Animated Sprite & Engine Core

An advanced, single-file HTML5 animated sprite engine featuring direct canvas renderers, algorithmic drawing tools, and audio synthesis capabilities.

Developed to showcase modern modular front-end programming techniques for the **#ShareMyProject** challenge.

## 🛠️ Advanced Core Architecture

- **Recursive Flood Fill (Bucket Tool):** Implements a customized Breadth-First Search (BFS) graph traversal algorithm to evaluate adjacent node states (grid pixels) and apply flood coloring without memory leaks or execution crashes.
- **Symmetry Mirroring Matrices:** Captures mapping coordinate transformations dynamically on mouse interact hooks, supporting Horizontal, Vertical, and Dual-Axis coordinate reflecting operations.
- **Multi-Frame Animation System:** Manages state matrices per canvas layer, caching sequential graphic arrays inside virtual stacks. The render loop draws to miniature canvas contexts to render live previews in real-time.
- **Procedural Chiptune Synthesizer:** Leverages the native Web Audio API to procedurally generate variable square and triangle wave synthesizer sweeps when drawing, copying, or exporting vectors.

## 💾 Core Technologies Utilized

- **CSS Variables:** Applied for immediate theme-wide matrix switches.
- **HTML5 Canvas:** Handles render processing pipelines.
- **Dynamic JavaScript (ES6+):** Coordinate conversion algorithm vectors, audio system nodes, state cloning, and canvas image serialization.

## 🚀 Run the Project Locally

1. Pull or download the source code locally.
2. Launch `index.html` inside a standard browser environment (e.g., via VS Code's **Live Server** extension) to automatically start up the audio engines and telemetry grids.
