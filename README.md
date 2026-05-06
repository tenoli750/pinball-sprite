# Pinball Sprite

This repository stores the current pinball sprite sheet used for quick game
prototyping and visual iteration.

## Asset

- `pinball-sprites.png` contains the sprite sheet.

## Usage notes

- Keep the exported filename stable so downstream prototypes can reference it.
- When replacing the image, preserve transparent background areas unless the
  consuming game is updated at the same time.
- Commit source artwork separately if the sprite sheet starts being generated
  from layered files.

## Handoff checklist

- Open the PNG and confirm it is not corrupted.
- Record any tile size or frame layout changes in this README.
