
Before taking this course, do PreCalculus [Intro to Matrices by Khan Academy](https://www.khanacademy.org/math/precalculus/precalc-matrices#intro-to-matrices).


# MIT Lecture 1

This lecture is the first introduction to the course. At the onset we look at two equations in a system of equations:

```
2x - y = 0
-x + 2y = 3

```
### Row Picture


There are different ways to solve this equation. If we solve it algebraically with the [elimination method](https://www.khanacademy.org/math/algebra/systems-of-linear-equations/modal/v/identifying-equivalent-systems-of-equations), we get ```[1,2]``` or that ```x = 1 , y = 2 ```.

You can also solve it by 


### Column Picture

```
x[2] y[-1].  =[0]
 [1]. [2].     [3]

```

This equation is asking for what (linear combination) of ```x``` and ```y``` do you need to find or solve to  ```0``` and ```3```.


So, if you add column 2```[-1,2]``` to column 1```[2,1]``` you will get ```[0,3]```. 

This is the primary understanding of linear combinations which is extremely important.

Important Question: Can any linear combination solve any b? Yes, except for if the columns end up in the same plane.




# MIT Lecture 2

```
x + 2y + z = 2
3x + 8y + z = 12
0x + 4y + z = 2
```


The first step of elimination is to multiply the first equation by the right number and subtract it from the second equation. The purpose is to knock out the x part of equation 2.  You do this by finding a pivot and a pivot is the first number that is not a 0 on the first row. You can therefore multiply this then subtract it from the second row to zero it out. This carries on into the other rows. To understand this more see [this Khan Academy exercise](https://www.khanacademy.org/math/precalculus/precalc-matrices/row-echelon-and-gaussian-elimination/v/matrices-reduced-row-echelon-form-2). This is also referred to as the Gaussian elimination.

```
1 2 4
2 4 8
6 4 5
```

The pivots in this example is 1,4,5. Pivots can never be 0 and if there is a 0, you can exchange it.


# MIT Lecture 3

- Matrix Multiplication (4 ways!)
- Inverse of A AB At
- Gauss Jordan / find A-1