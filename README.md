# RZF

Primary order research conducted by Sir Richard Southwell https://youtu.be/t9L05SWzdOc?t=380. 

Attempts to generate well-ordered vs non-well ordered visual multway system via python/networkx based on the Collatz-like functions. Certain Collatz-like functions, when altering either the first or second parameter (based on whether the input is even/odd), will generate a well-ordered visual multiway system, while others appear to be random with apparant structure, even out to very large integer inputs.

Known well-ordered parameters
(1+x), 2x
(1+2x),2x
2+2x, 2x
3x, 2x
4x, 2x
1+4x, 2x

Known nonwell-ordered parameters
(1+3x), 2x
2+x, 2x
2+3x, 2x
3+3x, 2x
