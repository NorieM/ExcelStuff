# Examples of LAMBDA functions

## Get all numbers from a cell.

`=LAMBDA(Item, IF(Item="", "", IF(ISNUMBER(LEFT(Item)+0), LEFT(Item)&GetNumbers(MID(Item,2,LEN(Item))),GetNumbers(MID(Item,2,LEN(Item))))))`
