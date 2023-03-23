# RZF

Primary theorical research inspired by Sir Richard Southwell [2013] https://youtu.be/t9L05SWzdOc?t=380.      

Primary analytical research inspired by ROBERT J. LEMKE OLIVER AND KANNAN SOUNDARARAJAN, "UNEXPECTED BIASES IN THE DISTRIBUTION OF CONSECUTIVE
PRIMES" [2016]. https://arxiv.org/abs/1603.03720v4   
and Chebyshev's Bias [1853] https://en.wikipedia.org/wiki/Chebyshev's_bias .  

This algorithm attempts to generate well-ordered vs non-well ordered visual multway system via python/networkx based on the Collatz-like functions.   
The parameters of original conjecture, where   

![image](https://user-images.githubusercontent.com/54874866/226145664-ed964e8c-9a24-4b04-b241-1c328261a939.png)


are known to always generate a number tree ending in 4,2,1, regardless of starting input, in both the Real and Complex number planes. Certain parameters, when inputed into a similar number tree, will generate a well-ordered visual multiway system, while others appear to be random. To generate such multiway systems visually, different starting parameters are inputted into the Collatz tree function to generate a multiway system and proceeds recursively to a given iteration.

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

