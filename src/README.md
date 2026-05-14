# Source Directory

This folder represents the planned source code structure for the 
HDR Imagery Dynamic Tone Mapping OpenFX plugin for DaVinci Resolve.

The files in this directory are placeholders that describe the expected 
software modules for a full implementation. The project focuses on 
software engineering planning, documentation, testing, and workflow 
management rather than delivering a completed plugin.

## Planned Modules

- `PluginEntry`: Handles OpenFX plugin registration and communication with DaVinci Resolve.
- `ToneMappingEngine`: Applies HDR tone mapping operations such as exposure adjustment, highlight roll-off, shadow recovery, contrast, and saturation protection.
- `LuminanceAnalyzer`: Analyzes frame brightness values to support dynamic tone mapping.
- `PresetManager`: Manages preset configurations such as Natural, Cinematic, Broadcast Safe, and Custom.
- `PreviewRenderer`: Handles preview modes such as full preview, split view, and side-by-side comparison.
