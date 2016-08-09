# parallel_bitonic_sorter
At its heart is repeated use of the butterfly structure. The algorithm proceeds by building sequences of keys that form a bitonic sequence: a sequence that first increases, and then decreases. It then uses butterfly structures to sort a bitonic sequence into either a decreasing or increasing sequence.   https://en.wikipedia.org/wiki/Bitonic_sorter
