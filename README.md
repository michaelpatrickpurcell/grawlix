# Grawlix
Grawlix is an abstract strategy game for two players that can be played in 15-30 minutes.

## The Typesetters' Game
A pair of typesetters once worked for a local newspaper. Every Sunday, they produced a set of comic strips. This was challenging because it was so different from their regular work. In particular, the cartoonists sometimes used strings of punctuation to represent profanity. The typesetters often had to improvise to find enough type to print those sections. So, they set aside the type that they had used for this purpose in a special case. Over time, they amassed a collection of thirty-six pieces of type. They had one for each of six different punctuation marks in each of six different typefaces.

One day, while preparing that week's comics, they noticed a curious phenomenon. They had arranged their collection of type in a square on their workbench. It was easy to ensure that every row and column had only one of each punctuation mark. It was easy to ensure that every row and column had only one of each typeface. Despite their best efforts, they could not find a way to do both at the same time. If they eliminated one punctuation mark and one typeface, then the problem was easy. If they added one punctuation mark and one typeface, then the problem was easy. There was something special about six.

They turned this puzzle into a two-player game that they could play as they worked. The rules were simple. Both players would grab a handful of type at the beginning of the day. Then, they would take turns playing by placing those pieces on the workbench in a grid. They had to place each piece next to a piece that was already in the grid. Each row and column could have only one of each punctuation mark and one of each typeface. The grid could have no more than six rows and six columns.

The game continued in this way until one player was unable to find a legal move. That player would be the loser of the game and would have to come in a few minutes early the next morning to make coffee.

## Components
Grawlix is a version of the typesetters' game. The gameplay is the same but the components are a bit different. In this version, plastic tiles are used in place of metal type. Also, different colors are used to distinguish tiles instead of different typefaces.

To play Grawlix, the players will need a flat _play area_ and thirty-six _tiles_. Each tile is labeled with one of six possible _glyphs_ and one six possible _colors_.  There is one tile for each possible combination of glyph and color.

The six glyphs are: @ (at symbol), \# (pound sign), $ (dollar sign), % (percent symbol), & (ampersand), and \* (asterisk). The six colors are: red, orange, yellow, green, blue, and purple.

![All of the tiles in a 6x6 grid](/Images/grid_image.png)

## The Grid
During the game, the players will place tiles in the play area. These tiles will be organized into a _grid_ made up of _rows_ and _columns_. A row is a group of tiles that are on the same horizontal line.  A column is a group of tiles that are on the same vertical line. The grid should have no more than six rows and six columns.

A _line_ is a generic term that can refer to either a single row or a single column of the grid. Each line can contain no more than one tile with each glyph and one tile with each color.

#### Notes
At the beginning of the game, the grid is empty.

Rows and columns do not need to be contiguous.  If two tiles are on the same line then they must have different glyphs and colors. This rule applies regardless of what tiles or gaps are between them along that line.

<!-- ![A grid containing thirty-three tiles](/Images/tableau.png) -->

## Set Up
The tiles should be placed face up to one side of the play area. These tiles comprise the _supply_. The supply should be arranged in a square. Each column should have all tiles of a given glyph and each row should have all tiles of a given color.

The players should decide which one of them will be the _first player_.

Starting with the first player, the players then take turns _drafting_ tiles. To draft a tile, a player should choose one tile from the supply and add that tile to their _hand_.

The set up phase is complete when both players have drafted four tiles.

#### Notes
All tiles should be visible to both players at all times.  This includes the supply, the grid and both players' hands.

## Gameplay
The players should take turns playing tiles from their hands until one of them is unable to do so.

After playing each tile the current player should draft a tile to replace the tile that they played. If there are no tiles in the supply, then they should skip this step.

If a player is unable to play a tile on their turn then that player loses the game.

### Playing Tiles
On their first turn, the first player should play a tile from their hand by placing it face up anywhere in the play area. This tile is the first tile in the grid.

On later turns, the current player should play a tile from their hand by placing it face up next to a tile in the grid. After it is played, this tile becomes part of the grid.

When a new tile is played it must be placed in the play area such that:
  1. At least one edge of the new tile is aligned with an edge of another tile in the grid.
  <!-- ![Legal placements for a new tile](/Images/adjacent.png) -->
  2. The glyph of the new tile is different from the glyph of every other tile in the:
     - row in which it is placed.
     - column in which it is placed.
  <!-- -->
  3. The color of the new tile is different from the color of every other tile in the:
     - row in which it is placed.
     - column in which it is placed.
  <!-- -->
  4. The grid has no more than six rows and six columns.

### Example 1
In the following example, it is early in the game. Three tiles are in the grid: the red & (ampersand), the blue # (pound sign), and the yellow * (asterisk).  The next player can place their tile in one of seven possible locations. These locations are indicated by the dotted squares in the diagram below.

![grid with three tiles seven possible next moves](/Images/small_example.png)

Consider the location labeled with the question mark. The only tile in this column is the red & (ampersand) and the only tile in this row is the yellow * (asterisk). So, the allowed glyphs and colors for a tile placed in this location are:
  - __Glyphs__: @ (at symbol), # (pound sign), $ (dollar sign), % (percent symbol);
  - __Colors__: orange, green, blue, or purple.

During the game, more tiles will be added to the grid. This will further restrict which tiles can be placed in each location.

### Example 2
In the following example, seventeen tiles are in the grid. The next player can place their tile in one of sixteen possible locations. These locations are indicated by the dotted squares in the diagram below.

The grid has six columns, so a tile cannot be placed in a new column. The grid only has five rows, so a tile can be placed in a new row.

![grid with seventeen tiles and sixteen possible next moves](/Images/big_example.png)

Consider the location labeled with the question mark. There are no tiles in this row. The tiles in this column are the blue @ (at symbol), orange * (asterisk), and green \$ (dollar sign). So, the allowed glyphs and colors for a tile placed in this location are:
  - __Glyphs__: # (pound sign), \% (percent symbol), \& (ampersand);
  - __Colors__: red, yellow, purple.

If a tile is placed in the location labeled with the question mark, then the grid will have six rows. If that happens, then future tiles cannot be placed in a new row. In particular, the location labeled with the exclamation point will become unavailable.

## Fun Facts
Grawlix is a term coined by [Mort Walker](https://en.wikipedia.org/wiki/Mort_Walker), creator of the Beetle Bailey comic strip. It is a name for a string of typographical symbols that writers use as a replacement for profanity.

The typesetters' game is a re-themed version of the [thirty-six officers problem](https://en.wikipedia.org/wiki/Mutually_orthogonal_Latin_squares#Thirty-six_officers_problem).

## Sourcing Components
The file [grawlix_tiles.stl](grawlix_tiles.stl) contains models for Grawlix tiles that can be 3D printed. A complete set of tiles is comprised of six batches. Each batch uses two colors of filament, a base color and an accent color. White or light gray works well for the base color. The accent colors can be any set of six distinct colors. The rules below suggest red, orange, yellow, green, blue, and purple. To print the tiles, start with the base color. Pause the printer when the glyphs begins printing.  Switch the filament to the desired accent color and then finish the print.

Alternatively, the tiles from the popular game [Qwirkle](https://boardgamegeek.com/boardgame/25669/qwirkle) can be used to play Grawlix.  Qwirkle uses one hundred eight wooden tiles. Each tile has one of six different symbols on it in one of six different colors. There are three copies of each tile. So, the tiles from Qwirkle can be repurposed to form three sets of Grawlix tiles.
