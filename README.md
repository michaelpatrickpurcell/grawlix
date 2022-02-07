# Grawlix
Grawlix is an abstract strategy game for two players that can be played in 15-30 minutes.

The file [grawlix_tiles.stl](grawlix_tiles.stl) contains models for the tiles that are need to play the game as described in these rules. Six batches are required to produce a complete set of tiles, one batch per color. The models are designed to have the filament switched during the print. Start each batch using the same base color. White or light gray work well for this purpose. Pause the printer when the glyph begins printing and switch the filament to the desired accent color.

Alternatively, the tiles from the popular game [Qwirkle](https://boardgamegeek.com/boardgame/25669/qwirkle) can be used to play Grawlix.  Qwirkle is played with one hundred eight wooden tiles. Each tile has one of six different symbols on it in one of six different colors. There are three copies of each tile. So, the tiles from Qwirkle can be repurposed to form three sets of tiles, each of which is equivalent to a complete set of Grawlix tiles.


## The Typesetters' Game
A pair of typesetters once worked for a local newspaper in an era when that kind of work was still done with a mechanical printing press rather than with a computer. Because cartoonists often replaced any profanity in their comic strips with strings of punctuation and other special characters, the typesetters had set aside the type that they used to print those characters in a special case. Their collection consisted of the type used to print six different special characters in each of six different typefaces.

One day, while preparing that week's Sunday comics, they noticed a curious phenomenon. Despite their best efforts, neither of the typesetters could devise a way to arrange the thirty-six pieces of type in a 6x6 grid such that every row and every column had one of each special character and one of each typeface.

Eventually, they turned this puzzle into a two-player game that they could play as they worked. Both players would grab a handful of type at the beginning of the day. They would then take turns choosing a piece of type from their hand and placing it on the workbench next to a piece of type that had been played previously.

Each new piece of type had to be placed in a row and column that did not already have a piece of type with the same special character or the same typeface. Also, to ensure that they could pack up when they went home for the evening without disrupting an incomplete game, the tiles on the workbench could span no more than six rows and six columns.

The game continued in this way, with players refreshing their hands as necessary, until one player was unable to find a legal move. That player would be the loser of the game and would have to come in a few minutes early the next morning to make coffee.

## Components
Grawlix is a version of the typesetters' game. While the gameplay is unchanged, the components are a bit different. In this version, plastic tiles are used in place of metal type and different colors are used to distinguish tiles instead of different typefaces.

To play Grawlix, the players will need a flat _play area_ and thirty-six _tiles_.
Each tile is labeled with one of six possible _glyphs_ and one six possible _colors_.  There is one tile for each unique combination of glyph and color.

The six glyphs are: @ (at symbol), \# (pound sign), $ (dollar sign), % (percent symbol), & (ampersand), and \* (asterisk). The six colors are: red, orange, yellow, green, blue, and purple.

![All of the tiles in a 6x6 grid](/Images/grid_image.png)

## The Grid
During the game, the players will place tiles in the play area. These tiles will be organized into a _grid_ made up of _rows_ and _columns_. A row is a group of tiles that are on the same horizontal line.  A column is a group of tiles that are on the same vertical line. The grid should have no more than six rows and six columns.

A _line_ is a generic term that can refer to either a single row or a single column of the grid. Each line can contain no more than one tile with each glyph and one tile with each color.

#### Notes
At the beginning of the game, the grid is empty.

Rows and columns do not need to be contiguous.  That is, if two tiles are on the same line then they must have different glyphs and colors, regardless of what tiles or gaps are between them along that line.

<!-- ![A grid containing thirty-three tiles](/Images/tableau.png) -->

## Set Up
All of the tiles should be placed face up to one side of the play area. These tiles comprise the _supply_. It may be helpful to arrange the supply as a 6x6 grid in which each column consists of all of the tiles of a given glyph and each row consists of all of the tiles of a given color.

The players should decide which one of them will be the _first player_.

Starting with the first player, the players then take turns _drafting_ tiles. To draft a tile, a player should choose one tile from the supply and add that tile to their _hand_.

The set up phase is complete when both players have drafted four tiles.

#### Notes
All tiles, including those in the supply, the grid, and the players' hands, should be visible to both players at all times.  

## Gameplay
The players should take turns playing tiles from their hands until one of them is unable to do so.

After playing each tile, if there are any tiles remaining in the supply, the current player should draft a tile to replace the one that they played.

If a player is unable to play a tile on their turn then that player loses the game.

### Playing Tiles
On their first turn, the first player should play a tile from their hand by placing it face up anywhere in the play area. This tile is the first tile in the grid.

On every subsequent turn, the current player should play one tile from their hand by placing it face up next to another tile in the play area. After it is played, this tile becomes part of the grid.

When a new tile is played it must be placed in the play area such that:
  1. At least one edge of the new tile is aligned with an edge of another tile in the grid.
  <!-- ![Legal placements for a new tile](/Images/adjacent.png) -->
  2. The glyph of the new tile is different from the glyph of every other tile in the
     - row in which it is placed.
     - column in which it is placed.
  <!-- -->
  3. The color of the new tile is different from the color of every other tile in the:
     - row in which it is placed.
     - column in which it is placed.
  <!-- -->
  4. The grid has no more than six rows and six columns.

### Example 1
In the following example, three tiles are in the grid: the red & (ampersand), the blue # (pound sign), and the yellow * (asterisk).  The next player can place their tile in one of seven possible locations, which are indicated by the dotted squares in the diagram below.

![grid with three tiles seven possible next moves](/Images/small_example.png)

Consider the location labeled with the question mark. The only tile in this column is the red & (ampersand) and the only tile in this row is the yellow * (asterisk). So, the allowed glyphs and colors for a tile placed in this location are:
  - __Glyphs__: @ (at symbol), # (pound sign), $ (dollar sign), % (percent symbol);
  - __Color__: orange, green, blue, or purple.

As more tiles are added to the grid during the game, more constraints will be added which further restrict which tiles can be placed in each location.

### Example 2
In the following example, seventeen tiles are in the grid. The next player can place their tile in one of sixteen possible locations, which are indicated by the dotted squares in the diagram below.

The grid has six columns, so a tile cannot be placed in a new column. The grid only has five rows, however, so a tile can be placed in a new row.

![grid with seventeen tiles and sixteen possible next moves](/Images/big_example.png)

Consider the location labeled with the question mark. There are no tiles in this row. The tiles in this column are the blue @ (at symbol), orange * (asterisk), and green \$ (dollar sign). So, the allowed glyphs and colors for a tile placed in this location are:
  - __Glyphs__: # (pound sign), \% (percent symbol), \& (ampersand);
  - __Color__: red, yellow, purple.

If a tile is placed in the location labeled with the question mark, or another location in the same row, then the grid will have six rows and future tiles cannot be placed in the location labeled with the exclamation point.

## Fun Facts
Grawlix is a term coined by [Mort Walker](https://en.wikipedia.org/wiki/Mort_Walker), creator of the Beetle Bailey comic strip, to describe a string of typographical symbols that writers, particularly cartoonists, use as a replacement for profanity.

The puzzle that the typesetters' game is based on is a re-themed version of the [thirty-six officers problem](https://en.wikipedia.org/wiki/Mutually_orthogonal_Latin_squares#Thirty-six_officers_problem).
