# Bloom Filters

#### This is a little project I wanted to get an experiance with
#### (More about [the 'Bloom Filter' hashing method](https://en.wikipedia.org/wiki/Bloom_filter))

## Code Files:

- #### main
First, it hashes into a bloom filter the strings of the 'DB_FILE',
Then, checks which of the strings in 'CHECK_FILE' is recognized as a part of 'DB_FILE'

- #### stats_sim
Simulates two *disjointed* sets of strings,
Makes the same check made in the 'main file',
and prints a statistical analysis about the amount of mistakes made in the simulation.
(Mistakes = false-positive calls)



## Text Files:

- #### "All" and "even"
Used as default inputs to be used by "main.py".

- #### More Checks *(folder)*:
Contains more inputs for "main.py".
