# vientos-iconset

## IcoMoon.io

1. Go to https://icomoon.io/app/#/select
2. Import Icons (`icomoon/selection.json`)
 * approve to load settings
3. Modify selection
4. Generate SVG & More (Download) *make sure to select Polymer checkbox in settings (gear icon)*
5. Overwrite
 * `cp <unpacked-archive>/selection.json icomoon/selection.json`
 * copy entire `<svg>...</svg>` element from `<unpacked-archive>/icomoon-polymer/icomoon-iconset-svg.html` and replace with it one in `vientos-iconset.svg`
 * remove all `class="path1" ` from replaced svg
