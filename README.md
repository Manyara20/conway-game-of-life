# conway-game-of-life

Conway’s Game of Life
Game of Life is a cellular automaton proposed by the mathematician John Horton Conway. 
The universe of Game of Life is an infinitely large plane with square cells, which are either in two states alive, or dead, bound by certain rules.

A live cell with less than two live neighbors dies.
A live cell with more than three live neighbors dies.
A dead cell with exactly three neighbors becomes alive.
A live cell with two or three neighbors continues to live.

Obsevations
I had a fun time implementing Game of Life in Rust. The development time of the program took a bit of time because 
the Rust compiler kept on complaining, but the execution was smooth. Whereas for other languages, we write the program,
and we might run into errors at runtime, then come again to debug the code.

The Rust compiler also gives us suggestions for the errors and warnings which beat compilers
of other programming languages. Often I was in doubt while checking the output because the program(in Rust)
gave the output that is desired in the very first trial. This shows the power of the Rust compiler; once the
code compiles then there is a high chance that the program might work.

The observations we saw coincides with the safety that Rust promises.
This is just the tip of the iceberg, Rust also provides a lot of other features like borrowers, concurrency, and so on. 
The future of Rust while looking at the current state is bright, but will it stand the test of time; only time will tell the tale.

#ZRustcean
