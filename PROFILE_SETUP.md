# Profile setup

This repository is ready to replace the contents of the `SofieneZayati/SofieneZayati` profile repository.

## Included animations

- Local animated neon header: `assets/profile-header.svg`
- Animated typing introduction
- Local animated idea-to-device pipeline: `assets/dev-pipeline.svg`
- Animated 3D contribution landscape
- Animated Pac-Man contribution graph
- Local animated footer: `assets/profile-footer.svg`

## GitHub Actions

Two workflows are included:

- `generate-3d-contributions.yml`
- `generate-pacman.yml`

After pushing, open the **Actions** tab and run both workflows manually once if their images are not visible yet. The Pac-Man workflow publishes its SVG files to the `output` branch.
