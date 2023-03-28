# RZF

WIP  

## Intro
Theoretical research inspired by Sir Richard Southwell [2013] https://youtu.be/t9L05SWzdOc?t=380.      

Analytical research inspired by ROBERT J. LEMKE OLIVER AND KANNAN SOUNDARARAJAN, "UNEXPECTED BIASES IN THE DISTRIBUTION OF CONSECUTIVE
PRIMES" [2016]. https://arxiv.org/abs/1603.03720v4 and Chebyshev's Bias [1853] https://en.wikipedia.org/wiki/Chebyshev's_bias.  

## Algo

This algorithm creates visual multiway systems via python/networkx based on rules of the Collatz Conjecture. These Collatz-tree-like structures are created by taking a starting number, n, and apply different rules depending on whether n is odd or even. Arrows in red show the first transformation, and arrows in blue show the second. After the transformation, the output of the function is inputted recursively, until the function terminates or expands to infinity.  

Some rules generate well-ordered multiway systems. 

1+x, 2x  
  
![image](https://user-images.githubusercontent.com/54874866/228117102-fb36c61c-ea10-41f3-be1a-28ae685b8afa.png)

1+2x, 2x  


![image](https://user-images.githubusercontent.com/54874866/228117808-aa65559f-d8c2-421c-9392-df507dc89699.png)

Other rules generate nonwell-ordered multiway systems.  
  
    
   
1+3x, 2x  
  
![image](https://user-images.githubusercontent.com/54874866/228118058-52c939b0-86d4-45aa-80d3-64f81008aa0f.png)
  
  
  
2+3x, 2x  

![image](https://user-images.githubusercontent.com/54874866/228118303-bcc7c3b4-113a-4acb-b834-9bb2f7e691d4.png)
    
    
This is a pursuit to understand why.   
  
## Collatz
The original conjecture, otherwise known as the 3n+1 problem, has been an unsolved puzzle in mathematics. If n is even, the number is halved, and if n is odd, it is multiplied by 3 and added to 1. In all cases of positive n, the function eventually terminates to 1. 
 
![image](https://user-images.githubusercontent.com/54874866/226145664-ed964e8c-9a24-4b04-b241-1c328261a939.png)

This conjecture can be demonstrated as a directed graph (https://en.wikipedia.org/wiki/Directed_graph). The figure below is a Directed Graph of all starting positive integers that terminate to 1 in less than 20 steps.  
  
  
![image](https://user-images.githubusercontent.com/54874866/227743100-259ffa97-4052-4405-afa8-89601df6ac93.png)


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

It is believed that relationships between well ordered and nonwell-ordered multiway systems generated with Complex numbers may have bearing in proving nontrivial zeros of the Riemann Zeta Function [1853] https://en.wikipedia.org/wiki/Riemann_hypothesis.

