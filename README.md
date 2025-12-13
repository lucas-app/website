# Flat Images (Landing Page)

This folder contains the apartment image set used on the main landing page.

## Folder

`website/flatimages/`

## Files in this set

- `flat-living.jpg`
- `flat-kitchen.jpg`
- `flat-dining.jpg`
- `flat-bathroom.jpg`
- `flat-masterroom.jpg`
- `flat-guestroom.jpg`
- `flat-terrace.jpg`

## Usage

How you reference these images depends on how the website is served.

### If `website/` is the site root (common for static sites)
Use:

- `./flatimages/flat-living.jpg` (relative)
- `/flatimages/flat-living.jpg` (absolute from site root)

### If you are importing assets in code (bundlers)
If your setup supports importing image files (for example via a bundler), you can import and use them in components. Keep the filenames stable so you do not have to update code references when swapping images.

## Conventions

- Filenames are lowercase and hyphenated, keep them stable.
- Photos should stay visually consistent (same apartment, same style).
- Avoid heavy filters or unrealistic colors, aim for natural light.

## Performance

- Prefer `webp` if you later optimize for speed.
- Compress images before committing when possible, without visible artifacts.

## Notes

These images are intended for use as landing page marketing assets.
Confirm usage rights under the image generation tool terms if they were AI-generated.
