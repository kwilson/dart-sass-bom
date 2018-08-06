# dart-sass-bom

Demo to show (potentially) broken function on importing a file with BOM marker using `dart-sass`.

Contains usage with `node-sass` for comparison.

## Structure
Contains `site.scss` which imports `_common.scss`. The imported file has been saved as UTF-8 with BOM.

## Run
`npm run build-dart`
`npm run build-node`

node-sass version compiles, dart-sass fails.
