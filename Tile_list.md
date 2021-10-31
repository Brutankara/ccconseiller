
Tiles are defined by its borders. Each tile may have three kinds of borders:


- G: Grass

- P: Path

- C: City



A tile with shield or monastery has an additional -S if it has shield and/or an additional -M if it has a monastery.
A path or a city border will be followed by a number, where borders with the same number and tile, represents connected path or cities within the same tile.

The borders are specified following clockwise order:
Example:

![](https://github.com/GermanCalderonLeiva/ccconseiller/blob/main/SampleTile.png?raw=true)

In this example, the tile will be named like this:

![](https://github.com/GermanCalderonLeiva/ccconseiller/blob/main/Sample_Tile_Example.png.png?raw=true)

So, the tile is identified like: P1GP1G

List of tiles

+P1GP1G x8

+GP1G-M x2

+GP1P1 x9

+GGG-M x4

+C1P1P1C1 x3

+C1P1P1C1-S x2

+GC1GC1 x1

+GC1GC1-S x2

+GC1GC2 x3

+C1GP1P1 x3

+C1P1P1G x3

+C1C1GG x3

+C1C1GG-S x2

+C1P1GP1 x4

+C1C2GG x2

+P1P2P3P4 x1

+C1P1P2P3 x3

+GP1P2P3 x4

+C1C1GC1 X2

+C1C1GC1-S x1

+C1C1P1C1 X1

+C1C1P1C1-S x2

+C1C1C1C1-S x1

+C1GGG  x5
