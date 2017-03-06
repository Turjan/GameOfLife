# GameOfLife
*An implementation of Conway's Game of Life in Java.*

## History
The **Game of Life** (often referred as Conway's Game of Life) 
is a cellular automata devised by mathematician John Conway in 1970.

If you are new to the Game of Life then I suggest that start your journey at the
[Wikipedia page](https://en.wikipedia.org/wiki/Conway's_Game_of_Life) and at the 
archived version of [Paul Callaghan's lifepage](http://www.radicaleye.com/lifepage/).

## Ambition

The ultimate goals of this project:
- Providing a graphical interface for browsing and selecting files containing life patterns 
- Processing the selected file and animate the pattern and it's next generations

## How to use it

The project written in Java and the only dependency right now is [zip4j] (http://www.lingala.net/zip4j/). 
If you are using Maven then just use my pom file from the repository. 

For stable versions use the **master branch**.

At this point the program only understands **.lif** files with **Life 1.05** format.
Read more about it [here](http://psoup.math.wisc.edu/mcell/ca_files_formats.html#Life%201.05).

## Credits

I am using **Alan Hensel**'s zip-compressed archive of Life patterns in the project.

Also, most of my knowledge about this topic comes from the lifepage of **Sir Paul Terence Callaghan**.
