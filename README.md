# bonsai-icons
A library of icons for the Bonsai visual programming language

## How to export

SVG files should be exported using [Scour](https://github.com/scour-project/scour) with the following command:

```scour -i file.svg -o build/file.svg --enable-id-stripping --enable-comment-stripping --remove-metadata --create-groups```

For example, to batch optimize all icons in the project, run the following shell script:

```for f in *.svg ; do scour -i "$f" -o "build/$f" --enable-id-stripping --enable-comment-stripping --remove-metadata --create-groups ; done```

## Cleanup guide

### Remove undesired offsets and groups

In case there are transform groups to invert the Y-axis coordinates, they can be removed by creating a new layer, cut-and-pasting the drawing to this new layer, and deleting the old layer.
