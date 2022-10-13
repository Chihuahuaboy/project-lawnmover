Michael Martinez
michael.mar413@csu.fullerton.edu

//Problem Definition
We will be attempting to find an algorithm for sorting the light and dark discs; Light discs on the left, dark discs on the right.

//sort_lawnmower
for(i = 0 until number of light discs):   
    if(disc if even(light))
        true
    else
        false
    for (checks if true; j = 0 less than the total list length - 2):
        if(current state is dark, and next state is light)
            swap discs



//Lawnmower StepCount
n/2 * (2n-1(2 + max(0,1)) + 2n -1(2 + max(0,1)))
= n/2 (2n-1(2 + 1) + 2n-1(2 + 1))
= n/2 (6n-3 + 6n-3)
= n/2 (12n - 6)
=6n^2 - 3n

//Efficiency
lim(n -> inf) (6n^2 -3n)/(n^2)
= 6
Efficiency = O(n^2)

//sort_alternate
for(i = 0 until number of light discs):
    for(j = 0 until number of total discs - 1):
        if(current state is dark, and next state is light):
            swap discs

//step count
(n + 1) * (2n - 1(1 + max(1)))
= (n+1) * (2n-1 (2))
= (n+1) * (4n - 2)
= 4n^2 + 2n - 2

//Efficiency
lim(n -> inf) (4n^2 + 2n -2)/n^2
= 4
Efficiency = O(n^2)



