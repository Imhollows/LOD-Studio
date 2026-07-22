<div align="center">

# LOD Studio

### The complete FiveM resource editing and optimization workspace

**Create, preview, edit, analyze, optimize, and export vehicles, clothing, textures, and maps from one Windows application.**

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-7b61ff)
![Architecture](https://img.shields.io/badge/architecture-64--bit-6f42c1)
![Status](https://img.shields.io/badge/status-Stable-success)
![License](https://img.shields.io/badge/license-Proprietary-red)

[Features](#features) •
[Installation](#installation) •
[Quick Start](#quick-start) •
[Supported Formats](#supported-formats) •
[License](#license)

</div>

---

## About LOD Studio

LOD Studio is an all-in-one Windows application built for FiveM creators, developers, modders, and server teams.

It provides a complete local workspace for managing vehicles, textures, clothing, maps, META files, and resource optimization without requiring multiple external applications.

LOD Studio combines real-time 3D previews, non-destructive editing, performance analysis, batch processing, automatic validation, detailed reports, and FiveM-ready exports in a single professional interface.

---

## Features

### Vehicle Editor

- Import individual vehicles or complete vehicle packs
- Automatically detect related `.yft`, `.ytd`, and META files
- Preview supported vehicle models in a real-time 3D viewport
- Rotate, zoom, pan, recenter, and inspect models
- Switch between available LOD levels
- Display meshes, materials, textures, bones, and collisions
- Inspect polygon, vertex, material, and texture statistics
- Edit vehicle colors, liveries, and supported visual properties
- Edit handling values using structured forms
- Edit `vehicles.meta`, `handling.meta`, `carcols.meta`, and `carvariations.meta`
- Access raw XML editing with syntax validation
- Compare original and modified values
- Detect incomplete or incorrectly structured vehicle resources

### 3D Resource Viewer

- Real-time model rendering
- Perspective and orthographic cameras
- Front, rear, side, top, and bottom views
- Wireframe mode
- Texture toggle
- LOD selection
- Collision visualization
- Material inspection
- Grid and axis display
- Configurable lighting and background
- PNG screenshot export
- Model statistics and diagnostics

### Texture Editor

- Open and edit supported texture formats
- Brush, eraser, fill, pipette, text, shape, and selection tools
- Layer-based editing
- Layer groups, visibility, opacity, locking, and duplication
- Brightness, contrast, saturation, hue, gamma, and exposure controls
- Crop, resize, rotate, mirror, and transform tools
- Alpha channel preservation
- Undo and redo history
- Real-time preview on supported 3D resources
- Save as a new file or replace the working copy
- Automatic backup before replacement
- Mipmap generation
- Texture format conversion

### Resource Optimization

- Analyze complete resources and packs
- Calculate resource size and estimated texture memory usage
- Inspect polygon and vertex distribution
- Detect missing LOD levels
- Detect oversized, duplicated, or uncompressed textures
- Identify unused files and invalid references
- Display an optimization score
- Separate errors, warnings, and recommendations
- Optimize textures without modifying the 3D model
- Resize and compress textures using configurable profiles
- Generate mipmaps
- Preserve normal maps, specular maps, text, and alpha channels
- Preview estimated savings before applying changes
- Compare file sizes before and after optimization

### Batch Optimization

- Optimize complete folders and resource packs
- Process hundreds of files through a task queue
- Pause, resume, or cancel operations
- Run tasks in the background
- Monitor the current file and overall progress
- Display elapsed and estimated remaining time
- Continue working while optimization tasks run
- Generate a complete result summary
- Export optimized resources as a ZIP archive

### Clothing Editor

- Import clothing resources and complete collections
- Detect `.ydd`, `.ytd`, `.ymt`, and related files
- Organize clothing by gender, category, drawable, and texture
- Preview supported clothing items on a 3D character
- Edit clothing textures using the integrated texture editor
- Create and manage texture variants
- Reorganize indexes
- Detect index conflicts
- Detect missing textures and incomplete collections
- Merge compatible clothing packs
- Generate a FiveM-ready resource structure
- Generate or update `fxmanifest.lua`

### Map and MLO Tools

- Import complete FiveM map resources
- Detect `.ymap`, `.ytyp`, `.ydr`, `.ybn`, `.ytd`, and related files
- Preview supported map content in 3D
- Navigate using orbit and free-camera controls
- Browse and search map objects
- Inspect object coordinates, rotation, dimensions, and LOD settings
- Display collisions and supported MLO information
- Detect missing models, textures, and dependencies
- Detect duplicate or potentially misplaced objects
- Analyze resource size and streaming load
- Identify potentially heavy areas
- Validate map resource structure before export

### META and XML Editing

- Structured editors for supported META files
- Descriptions and validation for known values
- Search and filtering
- Original and modified value comparison
- Raw XML mode
- Syntax highlighting
- Line numbers
- Search and replace
- Automatic formatting
- Real-time validation
- Error location and diagnostic messages

### Project Management

- Create and open LOD Studio projects
- Open complete FiveM resource folders
- Import selected files
- Drag-and-drop support
- Recently opened projects
- Automatic project saving
- Non-destructive workspace
- Original files remain protected
- Automatic backups
- Manual restoration points
- Full undo and redo history
- Compare original and modified files
- Restore previous versions
- Search and filter resources
- Track all unexported modifications

### Validation and Diagnostics

LOD Studio can detect and report:

- missing files;
- invalid file references;
- incorrect resource structure;
- malformed META or XML files;
- oversized textures;
- missing mipmaps;
- duplicate files;
- unused files;
- missing LOD levels;
- heavy models;
- missing collisions;
- conflicting clothing indexes;
- missing map dependencies;
- export configuration issues.

Each diagnostic includes:

- severity;
- affected file;
- explanation;
- estimated impact;
- recommended solution;
- automatic correction when supported.

### Reports and Export

- Export complete optimized resources
- Preserve the original folder structure
- Generate FiveM-ready ZIP archives
- Include required `stream` and `data` folders
- Validate `fxmanifest.lua`
- Exclude backups and temporary files
- Generate detailed optimization reports
- Export reports as HTML, JSON, CSV, or PDF
- Display file-by-file changes
- Compare total size before and after processing

---

## Interface

LOD Studio uses a compact professional desktop interface designed for large FiveM projects.

The main workspace includes:

- a resource browser;
- a real-time 3D viewport;
- a 2D texture editor;
- contextual resource tabs;
- properties and META panels;
- optimization statistics;
- diagnostic messages;
- background task progress;
- logs and notifications;
- a persistent status bar.

The application includes dark, light, and high-contrast display modes.

---

## Installation

1. Open the repository's **Releases** section.
2. Download the latest Windows installer.
3. Run `LOD-Studio-Setup.exe`.
4. Follow the installation wizard.
5. Launch LOD Studio from the desktop shortcut or Start menu.

A portable version may also be included with selected releases.

> Windows may display a security confirmation when launching a newly downloaded executable. Confirm that the installer was downloaded from the official LOD Studio release page before continuing.

---

## System Requirements

### Minimum

- Windows 10 64-bit
- 64-bit dual-core processor
- 8 GB RAM
- DirectX 11-compatible graphics card
- 2 GB of available storage
- 1280 × 720 display

### Recommended

- Windows 11 64-bit
- Modern 6-core or better processor
- 16 GB RAM or more
- Dedicated DirectX 12-compatible graphics card
- SSD storage
- 1920 × 1080 display or higher

Large vehicle packs, clothing collections, and maps may require additional memory and storage.

---

## Quick Start

### Open a resource

1. Launch LOD Studio.
2. Select **Open Folder** or drag a resource folder into the application.
3. Wait for the resource analysis to complete.
4. Select a detected vehicle, clothing item, texture, or map from the resource browser.
5. Open the relevant editor tab.

### Optimize a resource

1. Open the **Optimization** tab.
2. Review detected errors, warnings, and recommendations.
3. Select an optimization profile.
4. Use the simulation option to preview estimated changes.
5. Start the optimization.
6. Review the final report.
7. Export the optimized resource as a ZIP archive.

### Edit a texture

1. Select a texture from the resource browser.
2. Open it in the integrated texture editor.
3. Apply the required changes.
4. Use **Apply and Replace** to update the working copy.
5. Review the resource in the 3D viewport.
6. Export the completed resource.

---

## Supported Formats

LOD Studio supports or recognizes selected files commonly used by GTA V and FiveM resources.

### Models and resources

```text
.yft
.ydd
.ydr
.ymap
.ytyp
.ybn
.ymt
.ymf
.ycd
```

### Textures and images

```text
.ytd
.dds
.png
.jpg
.jpeg
.tga
```

### Configuration and scripts

```text
.meta
.xml
.lua
.json
```

Support may vary depending on the format and operation. Some formats may be available for inspection or preview while modification remains restricted to operations that can be performed safely.

---

## File Safety

LOD Studio uses a non-destructive editing workflow.

The application separates:

1. original source files;
2. project working files;
3. exported files.

Before replacing or modifying a supported file, LOD Studio creates a backup or restoration point. Original files are never silently overwritten.

For additional safety:

- verify exports before replacing live server resources;
- keep external backups of important projects;
- test optimized resources on a development server first;
- do not interrupt the application during a final export.

---

## Privacy

Core editing, analysis, optimization, and export operations are performed locally on the user's computer.

LOD Studio does not require resource files to be uploaded to an external server for its primary functionality.

Any optional online service must be configured and enabled explicitly by the user.

---

## Screenshots

Add project screenshots to a `docs/images` directory and reference them here:

```md
![Vehicle Viewer](docs/images/vehicle-viewer.png)
![Texture Editor](docs/images/texture-editor.png)
![Optimization Report](docs/images/optimization-report.png)
```

---

## Bug Reports

Use GitHub Issues to report reproducible bugs.

Include:

- LOD Studio version;
- Windows version;
- affected resource type;
- exact steps to reproduce the issue;
- expected and actual behavior;
- relevant log output;
- screenshots when useful.

Only provide sample files when you own them or have permission to share them.

Do not upload paid, leaked, encrypted, escrow-protected, or copyrighted third-party resources.

---

## Security

Do not publish sensitive security vulnerabilities in public GitHub issues.

Privately report issues involving:

- arbitrary file access;
- unsafe archive extraction;
- code execution;
- credential exposure;
- update-system vulnerabilities;
- malicious plugins;
- data loss or file corruption.

---

## Legal Notice

LOD Studio does not provide tools for bypassing:

- resource encryption;
- Cfx.re Asset Escrow;
- software licenses;
- access restrictions;
- copyright protections;
- third-party security mechanisms.

Users are responsible for ensuring they have permission to view, modify, optimize, and distribute every resource processed with the application.

---

## License

Copyright © 2026 **LOD Studio**. All rights reserved.

LOD Studio and its source code are proprietary and confidential.

You may not copy, modify, distribute, sublicense, sell, reverse engineer, decompile, or create derivative works based on this software without prior written permission from the copyright holder.

See the [`LICENSE`](LICENSE) file for the complete terms.

---

## Disclaimer

LOD Studio is an independent project.

It is not affiliated with, endorsed by, or sponsored by Rockstar Games, Take-Two Interactive, Cfx.re, or FiveM.

FiveM, Grand Theft Auto V, Rockstar Games, and all related names and trademarks belong to their respective owners.

---

<div align="center">

### LOD Studio

**Build. Inspect. Optimize.**

</div>
