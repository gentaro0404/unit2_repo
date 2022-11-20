# Quiz018

## Create a function to help Lily

Lily was crossing a forest when she realizes that there is a tiger ahead of her who has seen Lily.
Lily quickly takes out a matchbox from her bag and burns a matchstick, because the tiger is afraid of fire.

A matchstick takes 5 seconds to burn completely.  The length of the forest that Lily needs to cross is "l" meters. Lily's speed is s cm/s

What is the minimum number of matchsticks Lily needs to burn to cross the forest safely?

| Input l:int s:int | Output:int   |
|-------------------|--------------|
| 100, 100          | 20 matches   |
| 250, 110          | 46 matches   |
| 500, 150          | 67 matches   |
| 12345, 123        | 2008 matches |



HL: Create the Truth table for the boolean equation

out = ABC+(A+B+C)+not(notA notB notC)

## :program
```.py
import math

number = int(input("Enter a number: "))
x = -12


while -12<=x<=15:
    power = math.pow(10, x)
    print(f"{number} * 10^{x} = {number*power}")
    x += 1

```

## Fig.1
![](quiz010.png)

##Flowchart:
![](quiz010_flow.JPG)
