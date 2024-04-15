# BrainF+
[![Documentation Status](https://readthedocs.org/projects/bfp/badge/?version=latest)](https://bfp.readthedocs.io/en/latest/?badge=latest)

_Brain is no longer F***ed_
## Installation
Nothing yet
## Usage
| Character      | Usage |
| ----------- | ----------- |
|`>`|Increment current working cell (Next Cell to the right)|
|`<`|Decrement current working cell (Next Cell to the left)|
|`+`|Increment the value in the current cell|
|`-`|Decrement the value in the current cell|
|`.`|Output the ASCII value for the current cell|
|`_`|Output the numerical value for the current cell|
|`,`|Accept first byte of input, and place it in the current cell|
|`[`|If the value of the current cell != zero, run until `]`|
|`]`|Jump back to `[`|
|`;`|Break Loop|
|`(`|Add arguments to method|
|`)`|End argument section|
|`{`|Begin function|
|`}`|End Function|
|`^(x)`|Set the current working cell to `x`|
|`^(\\)`|Set the current working cell to the value of the current cell|
|`^(\\x)`|Set the current working cell to the value cell `x`|
|`=(x)`|Copy value of current cell to cell `x`|
|`%`|Call Function at current cell|
|`&`|Retain value of cell after function returns|
|`:`|Open Dev Help|
|`}`|End Function|
|`^(x)`|Set the current working cell to `x`|
|`=(x)`|Copy value of current cell to cell `x` (Copy To)|
|`@(x)`|Copy value from cell `x` to current cell (Copy From)|
|`%`|Call Function at current cell|
|`!(x)`|Call function at cell `x` **WITHOUT MOVING**|
|`&`|Retain value of cell after function returns|
|`:`|Open Dev Help|
