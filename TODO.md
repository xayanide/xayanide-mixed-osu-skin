# todo

- blank images and audio files must have the same metadata according to their file type. their file sizes, date modified and date created. 95 bytes for blank images, 44 bytes for blank audio files.
- blank images must be SD. Their file names should not be suffixed with `@2x`.
- replace `mode-{n}-med` elements. must follow recommended `@2x` sizes (256x256)
- replace `mode-{n}-small` elements. must follow recommended `@2x` sizes (64x64)
- **instafade**: `@2x` elements for `score-{n}` and `default-{n}`. must be visually the same size as SD in-game
- **classic**: finish `hitcircle@2x.png` and `hitcircleoverlay@2x.png`, equivalent of the instafade variant, may need its origins
- find origin for followpoint-{n} and their `@2x` elements. must be visually the same size as SD in-game
- replace mod icons. must have correct labels and look exactly like lazer's. must follow recommended `@2x` sizes (128x128).
- replace ranking letters. must look exactly like lazer's. `ranking-{n}-small` must follow recommended `@2x` sizes (68x80).
- create SD elements from all `@2x` elements
- try to override default elements that were prefixed with `TODO-` with files equivalent to them 
- complete credits-licenses.txt
- **impossible**: find a way to get rid of the rotating panel lights from ranking panel (score and results screen) on osu! stable
