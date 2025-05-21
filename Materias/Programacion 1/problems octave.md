# PROBLEMS 2.11 

## Problem 1
Create a row vector that has the following elements: $3,\; 4\times 2.55,\; \frac{68}{16},\; 45,\; \sqrt[3]{110},\; \cos(25^\circ),\; 0.05$.

```octave
format short g
v1 = [3, 4*2.55, 68/16, 45, nthroot(110, 3), cosd(25), 0.05];
v1
```

```
v =

 Columns 1 through 6:

            3         10.2         4.25           45       4.7914      0.90631

 Column 7:

         0.05

```


## Problem 2

Create a row vector that has the following elements: $\frac{54}{3+4.2^2},\; 32,\; 6.3^2-7.2^2,\; 54,\; e^{3.7},\; \sin(66^\circ)+\cos\Bigl(\frac{3\pi}{8}\Bigr)$.

```octave
format short g
v = [54/(3+4.2^2), 32, 6.3^2-7.2^2, 54, exp(3.7), sind(66)+cos((3*pi)/8)];
v
```

```
v =

       2.6163           32       -12.15           54       40.447       1.2962

```

## Problem 3
Create a column vector that has the following elements: $25.5, \frac{14\,\tan(58^\circ)}{2.1^2+11}, 6!, 2.7^4, 0.0375, \frac{\pi}{5}$

```octave
format short g
v = [25.5; (14*tand(58))/(2.1^2+11); factorial(6); 2.7^4; 0.0375; pi/5];
v
```

```
v =

         25.5
       1.4539
          720
       53.144
       0.0375
      0.62832

```

## Problem 4
Create a column vector that has the following elements: $\frac{32}{3.2^2}, \sin^2(35^\circ), 6.1, \ln(29^2), 0.00552,\ln^2(29), 133$

```octave
format short g
v = [32/3.2^2; sind(35)^2; 6.1; log(29^2); 0.00552; (log(29))^2; 133];
v
```

```
v =

         12.5
        8.558
       2.6882
       10.625
        13.35

```

## Problem 5
Define the variables $x = 0.85$ $y = 12.5$ and then use them to create a column vector that has the following elements: $y, y^x, \ln\Bigl(\frac{y}{x}\Bigr), y\cdot x, x+y$

```octave
format short g

x = 0.85;
y = 12.5;

v = [y; y^x; log(y/x); y*x; x+y];
v
```


```
v =

          3.5        12.25     -0.54688        -22.4       1.8708
```

## Problem 6
Define the variables $a = 3.5$ y $b = - 6.4$ and then use them to create a row vector that has the following elements: $a,\; a^2,\; \frac{a}{b},\; a\cdot b,\; \sqrt{a}$

```octave
format short g

a = 3.5;
b = -6.4;
v = [a, a^2, a/b, a*b, sqrt(a)];
v
```

```
v =

          3.5        12.25     -0.54688        -22.4       1.8708
```

## Problem 7
Create a row vector in which the first element is $2$ and the last element is $37$, with an increment of $5$ between the elements $(2, 7, 12, \dots, 37)$.
```octave
format short g

v = 2:5:37;
v
```

```
v =

 Columns 1 through 6:

            2            7           12           17           22           27

 Columns 7 and 8:

           32           37

```

## Problem 8
Create a row vector with $9$ equally spaced elements in which the first element is $81$ and the last element is $12$.

```octave
format short g

v = linspace(81, 12, 9);
v
```

```
v =

 Columns 1 through 6:

           81       72.375        63.75       55.125         46.5       37.875

 Columns 7 through 9:

        29.25       20.625           12

```


## Problem 9
Create a column vector in which the first element is $22.5$, the elements decrease with increments of $-2.5$, and the last element is $0$. (A column vector can be created by the transpose of a row vector.)

```octave
format short g

v = (22.5:-2.5:0);
w = v';
w
```

```
w =

         22.5
           20
         17.5
           15
         12.5
           10
          7.5
            5
          2.5
            0

```

## Problem 10
Create a column vector with $15$ equally spaced elements in which the first element is $-21$ and the last element is $12$.

```octave
format short g

v = linspace(-21, 12, 15);
w = v';
w

```

```
w =

          -21
      -18.643
      -16.286
      -13.929
      -11.571
      -9.2143
      -6.8571
         -4.5
      -2.1429
      0.21429
       2.5714
       4.9286
       7.2857
       9.6429
           12

```
