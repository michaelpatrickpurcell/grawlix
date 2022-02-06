# Grawlix
Grawlix is an abstract strategy game for two players that can be played in 15-30 minutes.


## Backstory
A pair of typesetters once worked for a local newspaper in an era when that kind of work was still done with a mechanical printing press rather than with a computer. Because cartoonists often replaced any profanity in their comic strips with strings of punctuation and other special characters, the typesetters had set aside the type that they used to print those characters in a special case. Their collection consisted of the type used to print six different special characters in each of six different typefaces.

One day, while preparing that week's Sunday comics, they noticed a curious phenomenon. Despite their best efforts, neither of the typesetters could devise a way to arrange the thirty-six pieces of type in a 6x6 grid such that every row and every column had one type of each special character and one of each typeface.

Eventually, they turned this puzzle into a two-player game that they could play as they worked. Both players would grab a handful of type at the beginning of the day. They would then take turns choosing a piece of type from their hand and adding it to a grid of previously played type on the workbench. Each new piece of type had to be placed in a row and column that did not already have a piece of type with the same special character or the same typeface. Furthermore, the grid could have no more than six rows and six columns.

The game continued in this way, with players refreshing their hands as necessary, until one player was unable to find a legal move. That player would be the loser of the game. Each day, the loser of the game had to take out the trash at the end of the shift.

Grawlix is a version of the typesetters' game. In this version, plastic tiles are used in place of metal type and different colors are used in place of different typefaces.


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

![Tableau with three tiles seven possible next moves](/Images/small_example.png)

Consider the location labeled with the question mark. The only tile in this column is the red & (ampersand) and the only tile in this row is the yellow * (asterisk). So, the allowed glyphs and colors for a tile placed in this location are:
  - __Glyphs__: @ (at symbol), # (pound sign), $ (dollar sign), % (percent symbol);
  - __Color__: orange, green, blue, or purple.

As more tiles are added to the tableau during the game, more constraints will be added which further restrict which tiles can be placed in each location.

### Example 2
In the following example, seventeen tiles are in the tableau. The next player can place their tile in one of sixteen possible locations, which are indicated by the dotted squares in the diagram below.

The tableau has six columns, so a tile cannot be placed in a new column. The tableau only has five rows, however, so a tile can be placed in a new row.

![Tableau with seventeen tiles and sixteen possible next moves](/Images/big_example.png)

Consider the location labeled with the question mark. There are no tiles in this row. The tiles in this column are the blue @ (at symbol), orange * (asterisk), and green \$ (dollar sign). So, the allowed glyphs and colors for a tile placed in this location are:
  - __Glyphs__: # (pound sign), \% (percent symbol), \& (ampersand);
  - __Color__: red, yellow, purple.

If a tile is placed in the location labeled with the question mark (or another location in the same row), then the tableau will have six rows and future tiles cannot be placed in the location labeled with the exclamation point.

## Fun Facts
Grawlix is a term coined by Mort Walker to describe a string of typographical symbols that writers, particularly cartoonists, use as a replacement for profanity.

The mechanics of the game are based on the the [thirty-six officers problem](https://en.wikipedia.org/wiki/Mutually_orthogonal_Latin_squares#Thirty-six_officers_problem).
