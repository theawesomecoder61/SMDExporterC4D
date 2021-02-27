# SMDExporterC4D
A Valve SMD exporter for Cinema 4D R16-R23

## Usage
1. Download the `.py` file to your Cinema 4D's scripts folder (`%APPDATA%\MAXON\<Cinema 4D folder>\library\scripts`)
2. Open Cinema 4D and register `export_smd` to your menus however you please

## Compatibility
- ✔ geometry (including normals, UVs)
- ✔ skeleton (including weights)
- ❌ animations

## Options
### Selected Objects
Considers only selected objects. By default, the script only considers top-level objects

### Separate Meshes
Exports each mesh as a separate `.smd` file.

### Scale
Resizes the exported geometry.

## Notes
- Tested on Windows using R16, R21, and R23
