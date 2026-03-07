# SuperVoxels2 Cinema 4D 2026 Plugins

<img width="2816" height="1536" alt="Logo_A2" src="https://github.com/user-attachments/assets/fd901670-5050-4144-b2d9-8488a6a8e253" />

Second version of a voxel-based generator/cloner for C4D 2026, now with **SuperBrick**.

## ⚠️ Important Installation Note
**SuperVoxels2** requires `tbb12.dll` to be present in the main Cinema 4D installation folder (where the `Cinema 4D.exe` is located) to start correctly.

## SuperVoxels2
**SuperVoxels2** is an advanced voxelization and cloning plugin based on the OpenVDB library. It allows you to transform geometry, splines, and particles into volumes and back into various output formats.

### Key Features:
- **Multiple Input Sources**: Voxelize polygons, splines, Thinking Particles, and shaders.
- **Versatile Output Modes**: 
  - **Polygon**: Generate high-quality meshes from volumes with adaptivity and smoothing (Relax).
  - **Clones**: Use volumes as a distribution source for MoGraph-style cloning.

- **Advanced Control**: Fine-tune voxel size, bandwidth, distance thresholds, and threading.
- **Data Transfer**: Transfer UVWs, vertex colors, and selection groups from source to output.

---

## SuperBricks
**SuperBricks** is a dedicated generator for creating highly customizable, bricks.

### Key Features:
- **Flexible Dimensions**: Define brick size in studs (Width, Length, Height).
- **Height Types**: Toggle between **Standard** and **Plate** height ratios.
- **Detailing**: Optional bottom tubes/bars and high-quality Boole-based merging for clean geometry.
- **Fillet Controls**: Independent fillet (rounding) settings for the brick base, studs, and tubes for realistic rendering.
- **Performance**: Optimized for either fast viewport preview or high-quality production mesh.

---

## Resources
- **GitHub Repository**: [Cinema4D_2026_Plugins](https://github.com/Remotion/Cinema4D_2026_Plugins)
- **Developer**: Remotion (c) 2013 - 2026
