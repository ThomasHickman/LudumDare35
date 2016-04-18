#LudumDare35 - Tessellate

An entry for Ludum Dare 35 Game Jam, with theam "Shape Shifter"

## Screenshots

## Description

A fast-paced adrenaline-pumping arcade shooter, Tessellate dares to take the Ludum Dare 35's theme - 'Shapeshift' - literally.

Play as a small but strong triangular CPU and make your way through an 80's tech themed shoot-em-up as you face an endless stream of opponent shapes. What makes your little triangle so special? Why, the power to grow more shapes on yourself as you crush your foes, of course! Mow down hordes of enemies, avoid bombs, and gain power as you assimilate your enemies and go from a mere triangle to a thousand-sided shooting machine!

## How to play

### Aim

The aim of the game is to get the most points by gaining shapes.

### Controls

- Use WASD for movement up, down left and right the screen
- Move mouse pointer to adjust the rotation for your player
- To shoot bullets from all your triangles, use the left mouse button
- To make all your rectangles emit damage, press the right mouse button
- Pause with 'Escape' key

### Enemy AI

When you destroy enough triangles and squares, you gain them into your object and gain their attacks. Bombs destroy large areas of the shape when you hit them and you do not gain anything when you collide with them. Pentagons heal the area that they collide with to full health.

## Source notes

To get the code, just clone this repository:

```bash
git clone git@github.com:ThomasHickman/LudumDare35.git
```

The assets in this game-jam are hosted in Google Drive:
https://drive.google.com/folderview?id=0B3DdC1eaTiECYzRuS0pIYVlHcFE&usp=sharing

If you want to run the game in gamemaker with the assets, you will need to load some folders from Google Drive into the main folder created by git (by either copying these folders, or creating symlinks (`mklink /D` in windows)).

The mappings that you will need to configure are as follows:

| Google Drive folder location | Folder to link to
| ---                          | ---
| other-assets                 | other-assets
| images                       | sprites/images
| background_images            | background/images
| sounds_music                 | sound/audio
