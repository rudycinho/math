## 2.11 PROBLEMS 
## Problem 1
Create a variable $a$ that is a row vector with the following elements: $9,\ 1,\ 3^2,\ \frac{7}{4},\ 0,\ 2.25 \times 8.5,\ 0.8,\ \sin\left(\frac{\pi}{8}\right)$
```octave
format short g
a = [9, 1, 3^2, 7/4, 0, 2.25*8.5, 0.8, sin(pi/8)];
a
```

```
a =

 Columns 1 through 6:
            9            1            9         1.75            0       19.125

 Columns 7 and 8:
          0.8      0.38268
```

## Problem 2
Create a variable $b$ that is a row vector with the following elements: $\sqrt{5.2^3},\ 6.71 \times 10^3,\ (3+5.1^2)\cos(53^\circ),\ 15.8,\ \sqrt[3]{90},\ \frac{\sin\left(\frac{\pi}{2}\right)}{3\tan(20^\circ)}$
```octave
format short g
b = [sqrt(5.2^3), 6.71*10^3, (3+5.1^2)*cosd(53), 15.8, nthroot(90,3), (sin(pi/2))/(3*tand(20))];
b
```

```
b =
       11.858         6710       17.459         15.8       4.4814      0.91583
```

## Problem 3
Create a variable $c$ that is a column vector with the following elements: $2.1 \times 10^{-2},\ \sin(1.7\pi),\ 28.5,\ 2.7^{\frac{4}{3}},\ \exp(3)$
```octave
format short g
c = [2.1*10^-2; sin(1.7*pi); 28.5; 2.7^(4/3); exp(3)];
c
```

```
c =
        0.021
     -0.80902
         28.5
       3.7597
       20.086

```

## Problem 4
Create a variable d that is a column vector with the following elements: $0.75 \times 5.2^{0.7},\ 11.1,\ \sqrt[3]{60},\ \tan\left(\frac{10\pi}{11}\right),\ \cos^2(5^\circ),\ 0.116$
```octave
format short g
d = [0.75*(5.2^0.7); 11.1; nthroot(60,3); tan((10*pi)/11); (cosd(5))^2; 0.116];
d
```

```
d =
       2.3783
         11.1
       3.9149
     -0.29363
       0.9924
        0.116
```

## Problem 5
Define the variables $x = 3.4$ and $y = 5.8$ and then use them to create a row vector (assign it to a variable named $e$) that has the following elements: $\frac{x}{y},\ x+y,\ x^y,\ x \cdot y,\ y^2,\ x$ 
```octave
format short g
x = 3.4;
y = 5.8;
e = [x/y, x+y, x^y, x*y, y^2, x];
e
```

```
e =
      0.58621          9.2       1209.4        19.72        33.64          3.4

```
## Problem 6
Define the variables $c = 4.5$ and $d = 2.8$ and then use them to create a column vector (assign it to a variable named $f$) that has the following elements: $d^2,\ c,\ c+d,\ c^d,\ d$. 
```octave
format short g
c = 4.5; 
d = 2.8; 
f = [d^2; c; c+d; c^d; d];
f
```

```
f =
         7.84
          4.5
          7.3
       67.452
          2.8
```
## Problem 7
Create a variable $g$ that is a row vector in which the first element is $3$ and the last element is $27$, with an increment of $4$ between the elements $(3, 7. 11..... 27)$. 
```octave
format short g
g = 3:4:27;
g
```

```
g =
 Columns 1 through 6:
            3            7           11           15           19           23
 Column 7:
           27
```
## Problem 8
Create a variable $h$ that is a row vector with eight equally spaced elements in which the first element is $68$ and the last element is $12$. 
```octave
format short g
h = linspace(68,12,8);
h
```

```
h =

 Columns 1 through 6:
           68           60           52           44           36           28

 Columns 7 and 8:
           20           12
```
## Problem 9
Create a variable $M$ that is a column vector in which the first element is 6.4, the elements increase with increments of 0.8, and the last element is 12. (A column vector can be created by the transpose of a row vector.) 
```octave
format short g
M = (6.4:0.8:12);
M = M';
M
```

```
M =
          6.4
          7.2
            8
          8.8
          9.6
         10.4
         11.2
           12

```
## Problem 10
Create a variable $N$ that is a column vector with seven equally spaced elements in which the first element is 44 and the last element is 23. (A column vector can be created by the transpose of a row vector.)
```octave
N = linspace(44,23,7);
N = N';
N
```

```
N =
           44
         40.5
           37
         33.5
           30
         26.5
           23

```