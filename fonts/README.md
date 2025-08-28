Place Font Awesome Free Solid font here to enable icon rendering on the overview page.

Recommended file:

- Font: Font Awesome 6 Free Solid
- File name: FontAwesome6Free-Solid.otf (or .ttf)

Only a tiny glyph subset is needed to keep firmware size small. The config includes:

- \uF0EB  (lightbulb)
- \uF863  (fan)

Download (manual):

1) Get the Font Awesome Free package from https://fontawesome.com/download (Free → Desktop → OTF/TTF).
2) From the package, copy the Solid font file (e.g., FontAwesome6Free-Solid.otf) into this `fonts/` folder.
3) Leave the file name as `FontAwesome6Free-Solid.otf` to match the path used in `remote-control.yaml`.

After placing the file, compile/flash ESPHome again. The Overview light and fan buttons will use these icons.
