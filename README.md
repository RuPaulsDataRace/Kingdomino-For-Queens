# Kingdomino-For-Queens
A little kingdomino dataset for people who want to do some analysis. All the tiles, all the time.

Each row has 9 fields: 
-------
+ **Tile Number**: The number on the back of the tile. The dataset is sorted in ascending order of this field.
+ **First Suit**: The suit on the left side of the tile when the tile is face up.
+ **First Suit Color**: The color of the first suit. This was included to make identifying suits easier.
+ **Second Suit**: The suit on the right side of the tile when the tile is face up.
+ **Second Suit Color**: The color of the second suit. This was included to make identifying suits easier.
+ **#Crowns on First Suit**: The number of crowns on the aforementioned first suit.
+ **#Crowns on Second Suit**: The number of crowns on the aforementioned second suit.
+ **First Suit and Crowns**: The number of crowns on the first suit concatenated with the name of the first suit.
+ **Second Suit and Crowns**: The number of crowns on the second suit concatenated with the name of the second suit.

Some Quick and Easy Counts:
------
| Suit   | Tile Count | Square Count | Crown Count | Count of Tiles with Crowns |
|--------|------------|--------------|-------------|----------------------------|
| Wheat  | 24         | 26           | 5           | 5                          |
| Forest | 18         | 22           | 6           | 6                          |
| Water  | 15         | 18           | 6           | 6                          |
| Grass  | 12         | 14           | 6           | 4                          |
| Swamp  | 9          | 10           | 6           | 4                          |
| Mine   | 6          | 6            | 7           | 5                          |


All Kingdomino Tiles in Order of Tile Number
------
 ![alt text](https://raw.githubusercontent.com/rupaulsdatarace/kingdomino-for-queens/master/kingdominoinordershifted.jpg)
