# DejaBrew — Blender Animation

## Project Structure

```text
.
├── assets/
│   ├── audio/          # Music and sound effects
│   ├── materials/      # Reusable materials and shaders
│   ├── models/         # 3D models and objects
│   └── textures/       # Images, logos, and textures
├── renders/            # Rendered frames and videos
└── scenes/
    └── main.blend      # Master animation scene
```

Each directory contains its own `README.md` with additional information.

## Getting Started

1. Clone the repository using Git or GitHub Desktop.
2. Open `scenes/main.blend` in Blender.
3. Use the same Blender version as the rest of the team.
4. Ensure external assets use relative paths.

## Collaboration Guidelines

- **Pull** the latest changes before working.
- Create a separate branch for your assigned task.
- Avoid editing the same `.blend` file simultaneously.
- Keep models and other assets in their designated directories.
- Commit and push your changes, then create a pull request.
- Keep the `main` branch stable.

## Git LFS

This repository uses Git LFS to manage Blender files and other large binary assets.

GitHub Desktop supports Git LFS automatically. Terminal users should run:

```bash
git lfs install
```

## Notes

- `scenes/main.blend` is the master scene and should be maintained by the assigned integrator.
- `scenes/main.blend1` is an automatic Blender backup and should not be committed.
- Keep textures such as `DejaBrew_Logo.png` inside `assets/textures/`.
- Generated renders should remain outside version control to minimize repository size.
