# turbo 40 go

Monoblock custom ergonomic keyboard with 40 keys and choc spacing.

## features

What sets this keyboard apart, is the custom bottom plate option, that allows you to use this keyboard directly on top of a MacBook keyboard on the go.
Each wing of the board is tilted 25 degrees inwards for a more comfortable hand position.

## creation

Files are generated with ergogen. The corresponding yaml file can be found within my own fork of the [ergogen repo](https://github.com/a-wark/ergogen/tree/turbo) in this [file](https://github.com/a-wark/ergogen/blob/turbo/input/turbo.yaml).

## source files

- gerber files
- 3d printable files
  - bottom_standard.stl => Normal bottom plate for the keyboard
  - bottom_grid.stl => MacBook keyboard grid for using this keyboard on the go

## parts list

| amount | part              | part name                    | note                        |
| ------ | ----------------- | ---------------------------- | --------------------------- |
| 1x     | controller        | nice!nano v2                 |
| 1 set  | sockets           | mill max low profile sockets |
| 1x     | battery           |                              |
| 1x     | battery connector | JST connector                |
| 1x     | on / off switch   |                              |
| 1x     | reset button      |                              |
| 40x    | hot swap sockets  |                              | for choc switches           |
| 40x    | smd diodes        |                              |
| 40x    | choc switches     |                              | I use `sunset` or `pro red` |
| 2x     | index keycaps     |                              |
| 6x     | convex keycaps    |                              | for thumbs                  |
| 32x    | normal keycaps    |                              |
| 12x    | screws            | M2 4mm                       |
