# Grawlix
Grawlix is a two-player, perfect-information, [abstract strategy game](https://en.wikipedia.org/wiki/Abstract_strategy_game) which is based on the [thirty-six officers problem](https://en.wikipedia.org/wiki/Mutually_orthogonal_Latin_squares#Thirty-six_officers_problem).

The name of the game refers to a term coined by Mort Walker to describe a string of typographical symbols that writers, particularly cartoonists, use as a replacement for profanity.

## Components
The only components required to play Grawlix are a flat _play area_ and thirty-six _tiles_.
Each tile is labeled with one of six possible _glyphs_ and one six possible _colors_.  There is exactly one tile for each unique combination of glyph and color.

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

![All of the pieces in a 6x6 grid](/Images/grid_image.png)

## Set Up
All of the tiles should be placed face up on one side of the play area. These tiles are called the _supply_. It may be helpful to arrange the supply as a 6x6 grid in which each column consists of all of the tiles of a given glyph and each row consists of all of the tiles of a given color.

The players should decide which one of them will be the _first player_.

Starting with the first player, the players then take turns _drafting_ tiles. To draft a tile, a player should choose one tile from the supply and add that tile to their _hand_.

The set up phase is complete when both players have drafted four tiles.

All tiles, both in the supply and in the players' hands, should be visible to both players at all times.  

At the beginning of the game, there are no tiles in the play area.

## Gameplay
The players will take turns playing tiles from their hands to the play area until one of them is unable to do so.

After playing each tile, if there are any tiles remaining in the supply then the current player should choose a tile from the supply and add it to their hand to replace the tile that they played.

If a player is unable to play a tile on their turn then that player loses the game.

### Playing Tiles
On their first turn, the first player should play a tile from their hand by placing it face up anywhere in the play area.

On every subsequent turn, the current player should play one tile from their hand by placing it face up next to another tile in the play area.

This ensures that the tiles in the play area will be aligned in a square grid made up of _rows_ and _columns_. A row is a group of tiles that are on the same horizontal line.  A column is a group of tiles that are on the same vertical line.

Rows and columns do not need to be contiguous.  That is, if two tiles are on the same line then they are in the same row or column, regardless of what tiles or gaps are between them along that line.

More explicitly, when a new tile is added to the play area it must be placed such that:
  1. At least one edge of the new tile is aligned with an edge of another tile in the play area.
  <!-- ![Legal placements for a new tile](/Images/adjacent.png) -->
  2. The glyph of the new tile is different from the glyph of every other tile in the
     - row in which it is placed.
     - column in which it is placed.
  <!-- -->
  3. The color of the new tile is different from the color of every other tile in the:
     - row in which it is placed.
     - column in which it is placed.
  <!-- -->
  4. After placing the new tile, the tiles in the play area span no more than six rows and six columns. In other words, there must be no more than six distinct rows and six distinct columns.

### Example
In the following example, three tiles are in the play area: the red ampersand, the blue pound sign, and the yellow asterisk.  The next player can place their tile in one of seven possible locations, which are indicated by the dotted squares in the diagram below.

![Play area with three tiles seven possible next moves](/Images/example_question.png)

Consider the location labeled with the question mark. The only other tile in the same column is the red & (ampersand) and the only other tile in this row is the yellow * (asterisk). So, the constraints on glyphs and colors for any tile placed in this location are:
  - __Glyphs__: @, #, $, % (anything but & or *);
  - __Color__: orange, green, blue, or purple (anything but red or yellow).

  <!-- 1. The only other tile in this column is the red ampersand. There are no tiles in this row. So, any tile that is placed here must be labeled with the at symbol, pound sign, dollar sign, percent symbol, or asterisk (i.e. anything but the ampersand) and must be orange, yellow, green, blue, or purple (i.e. anything but red).
  2. The other tiles in this column are the blue pound sign and the yellow asterisk. There are no tiles in this row. So, any tile that is placed here must be labeled with the at symbol, dollar sign, percent symbol, or ampersand and must be red, orange, green, or purple.
  3. There are no other tiles in this column. The other tiles in this row are the red ampersand and the blue pound sign. So, any tile that is placed here must be labeled with the at symbol, dollar sign, percent symbol, or asterisk and must be orange, yellow, green, or purple.
  4. The constraints for this location are the same as for 3.
  5. The only other tile in this column is the red ampersand. The only other tile in this row is the yellow asterisk. So, any tile that is placed here must be labeled with the at symbol, pound sign, dollar sign, or percent symbol and must be orange, green, blue, or purple.
  6. There are no other tiles in this column. The only other tile in this row is the yellow asterisk. So, any tile that is placed here must be labeled with the at symbol, pound sign, dollar sign, percent symbol, or ampersand (anything but the asterisk) and must be red, orange, gree, blue, or purple (anything but yellow).
  7. The constraints for this location are the same as those for 2. -->
