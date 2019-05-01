# bonsai-icons
A library of icons for the Bonsai visual programming language

## How to export

SVG files can be exported from Inkscape, using **Save As...** > **Optimized SVG**. Ensure the following checkboxes are enabled:

1. **Options** > *Work around renderer bugs*
2. **Options** > *Collapse groups*
3. **Options** > *Create groups for similar attributes*
4. **SVG Output** > *Remove metadata*
5. **SVG Output** > *Remove comments*

## Cleanup guide

### Remove undesired offsets and groups

In case there are transform groups to invert the Y-axis coordinates, they can be removed by creating a new layer, cut-and-pasting the drawing to this new layer, and deleting the old layer.
