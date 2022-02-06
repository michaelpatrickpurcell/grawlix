# Grawlix
Grawlix is a two-player, perfect-information, [abstract strategy game](https://en.wikipedia.org/wiki/Abstract_strategy_game) which is based on the [thirty-six officers problem](https://en.wikipedia.org/wiki/Mutually_orthogonal_Latin_squares#Thirty-six_officers_problem).

The name of the game refers to a term coined by Mort Walker to describe a string of typographical symbols that writers, particularly cartoonists, use as a replacement for profanity.

## Components
The only components required to play Grawlix are a flat _play area_ and thirty-six _tiles_.
Each tile is labeled with one of six possible _glyphs_ and one six possible _colors_.  There is one tile for each unique combination of glyph and color.

The six possible glyphs are:
  - @ (at symbol)
  - \# (pound sign)
  - $ (dollar sign)
  - % (percent symbol)
  - & (ampersand)
  - \* (asterisk)

The six possible colors are:
  - Red
  - Orange
  - Yellow
  - Green
  - Blue
  - Purple

![All of the tiles in a 6x6 grid](/Images/grid_image.png)

## The Tableau
During the game, the tiles will place tiles in the play area. These tiles will be organized into a _tableau_ made up of _rows_ and _columns_. A row is a group of tiles that are on the same horizontal line.  A column is a group of tiles that are on the same vertical line. The tableau should have no more than six rows and six columns.

A _line_ is a generic term that can refer to either a single row or a single column of the tableau. Each line can contain no more than one tile labeled with each glyph and one tile of each color.

#### Notes
At the beginning of the game, the tableau is empty.

Rows and columns do not need to be contiguous.  That is, if two tiles are on the same line then they are in the same row or column, regardless of what tiles or gaps are between them along that line.

![A tableau containing thirty-three tiles](/Images/tableau.png)

## Set Up
All of the tiles should be placed face up to one side of the play area. These tiles comprise the _supply_. It may be helpful to arrange the supply as a 6x6 grid in which each column consists of all of the tiles of a given glyph and each row consists of all of the tiles of a given color.

The players should decide which one of them will be the _first player_.

Starting with the first player, the players then take turns _drafting_ tiles. To draft a tile, a player should choose one tile from the supply and add that tile to their _hand_.

The set up phase is complete when both players have drafted four tiles.

#### Notes
All tiles, including those in the supply, the tableau, and the players' hands, should be visible to both players at all times.  

## Gameplay
The players should take turns playing tiles from their hands until one of them is unable to do so.

After playing each tile, if there are any tiles remaining in the supply, the current player should draft a tile to replace the one that they played.

If a player is unable to play a tile on their turn then that player loses the game.

### Playing Tiles
On their first turn, the first player should play a tile from their hand by placing it face up anywhere in the play area. This tile is the first tile in the tableau.

On every subsequent turn, the current player should play one tile from their hand by placing it face up next to another tile in the play area. After it is played, this tile becomes part of the tableau.

When a new tile is played it must be placed in the play area such that:
  1. At least one edge of the new tile is aligned with an edge of another tile in the tableau.
  <!-- ![Legal placements for a new tile](/Images/adjacent.png) -->
  2. The glyph of the new tile is different from the glyph of every other tile in the
     - row in which it is placed.
     - column in which it is placed.
  <!-- -->
  3. The color of the new tile is different from the color of every other tile in the:
     - row in which it is placed.
     - column in which it is placed.
  <!-- -->
  4. The tableau has no more than six rows and six columns.

### Example 1
In the following example, three tiles are in the tableau: the red & (ampersand), the blue # (pound sign), and the yellow * (asterisk).  The next player can place their tile in one of seven possible locations, which are indicated by the dotted squares in the diagram below.

![Tableau with three tiles seven possible next moves](/Images/example_question.png)

Consider the location labeled with the question mark. The only tile in this column is the red & (ampersand) and the only tile in this row is the yellow * (asterisk). So, the allowed glyphs and colors for a tile placed in this location are:
  - __Glyphs__: @ (at symbol), # (pound sign), $ (dollar sign), % (percent symbol);
  - __Color__: orange, green, blue, or purple.

As more tiles are added to the tableau during the game, more constraints will be added which further restrict which tiles can be placed in each location.

### Example 2
In the following example, seventeen tiles are in the tableau. The tableau has five rows and six columns. The next player can place their tile in one of sixteen possible locations, which are indicated by the dotted squares in the diagram below.

![Tableau with seventeen tiles and sixteen possible next moves](/Images/big_example.png)

The tableau already has six columns, so a tile cannot be placed in a new column. The tableau only has five rows, so a tile can be placed in a new row.

Consider the location labeled with the question mark. There are no tiles in this row. The tiles in this column are the blue @ (at symbol), orange * (asterisk), and green \$ (dollar sign). So, the allowed glyphs and colors for a tile placed in this location are:
  - __Glyphs__: # (pound sign), \% (percent symbol), \& (ampersand);
  - __Color__: red, yellow, purple.

If a tile is placed in the location marked by the question mark (or another location in the same row), then the tableau will have six rows and future tiles cannot be placed in the location marked by the exclamation point.
