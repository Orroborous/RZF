# RZF

Primary order research conducted by Sir Richard Southwell https://youtu.be/t9L05SWzdOc?t=380. 

Attempts to generate well-ordered vs non-well ordered visual multway system via python/networkx based on the Collatz-like functions. Certain Collatz-like input paramteres based on the original conjecture where

![image](https://user-images.githubusercontent.com/54874866/226145664-ed964e8c-9a24-4b04-b241-1c328261a939.png)


will generate a well-ordered visual multiway system, while others appear to be random, even out to very large integer inputs. To generate such multiway systems visually, the paramters are inversed where the Collatz tree (attempts) to start at node 1 and proceeds depending on the value of the input.

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
