# Real 3D Models

Drop NASA / Sketchfab `.glb` files here to replace the procedural ships:

- `hail-mary.glb` — fictional Hail Mary spacecraft
- `discovery.glb` — Space Shuttle Discovery (orbiter + ET + SRBs stack)
- `artemis.glb` — SLS + Orion stack

## Where to get models

**NASA 3D Resources** (https://nasa3d.arc.nasa.gov/):
- Browse models, download as `.obj` or `.stl`
- Convert to `.glb` using https://anyconv.com/obj-to-glb-converter/ or Blender

**Sketchfab** (https://sketchfab.com/):
- Search "Space Shuttle" / "SLS" / "Orion"
- Filter by "Downloadable" + license
- Download as `.glb`

**Direct examples**:
- Space Shuttle: https://nasa3d.arc.nasa.gov/detail/space-shuttle-orbiter
- Saturn V: https://nasa3d.arc.nasa.gov/detail/saturn-v
- SLS: https://nasa3d.arc.nasa.gov/detail/sls-blk-1

## Tips

- Each file should be **under ~20MB** so GitHub Pages serves them fast
- Scale is adjusted automatically by the game (`GLB_SCALE` in index.html)
- If the model loads but looks wrong size, tweak `GLB_SCALE` for your ship type
- Check the browser console for `[Stellar Drift] Loaded real model for X` to confirm it loaded

## License

NASA models are mostly public domain. Sketchfab models have varied CC licenses — check each one. Don't commit copyrighted models without permission.
