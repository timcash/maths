# maths - 
*math notes for differential: solve with undermined coefficients.*
#
### question 9, 4.5.21
```
solve y''(θ)+12y'(θ)+37y(θ)=Power[e,-6θ]cosθ for θ  
```
 https://www.wolframalpha.com/input/?i2d=true&i=solve+y%27%27%5C%2840%29%CE%B8%5C%2841%29%2B12y%27%5C%2840%29%CE%B8%5C%2841%29%2B37y%5C%2840%29%CE%B8%5C%2841%29%3DPower%5Be%2C-6%CE%B8%5Dcos%CE%B8+for+%CE%B8++
 #
### question 10, 4.5.25

```solve
{z''(x) + z(x) = 9 e^(-6 x), z(0) = 0, z'(0) = 0}
```

https://www.wolframalpha.com/input/?i2d=true&i=z%27%27%5C%2840%29x%5C%2841%29+%2B+z%5C%2840%29x%5C%2841%29+%3D+9Power%5Be%2C%5C%2840%29-6x%5C%2841%29%5D%5C%2844%29+z%5C%2840%290%5C%2841%29%3D0%5C%2844%29+z%27%5C%2840%290%5C%2841%29%3D0
#
### question 15, 4.5.43

Given the general form for the differenrial equation for the spring-mass system:
$$
my''+by'+ky = g(t)
$$
and
$$
mass: m = 1,
spring-constant: k = 6,damping-coefficient: b=5, start: y(0) = \frac{1}{2}, rest: y'(0) = 0.
$$

$$
\implies y''+5y'+6y=6sin(2t)
$$

Then solve above for $t$:
```
solve y''(t)+5y'(t)+6y(t)=6*sin(2t) for t
```
https://www.wolframalpha.com/input/?i2d=true&i=solve+y%27%27%5C%2840%29t%5C%2841%29%2B5y%27%5C%2840%29t%5C%2841%29%2B6y%5C%2840%29t%5C%2841%29%3D6*sin%5C%2840%292t%5C%2841%29+for+t

The above gives:
```
y(t) = c_1 e^(-3 t) + c_2 e^(-2 t) + 3/26 sin(2 t) - 15/26 cos(2 t)
```
e.i.
$$
y(t) = c_1 e^{-3t} + c_2 e^{-2 t} + \frac{3}{26}sin(2t) - \frac{15}{26} cos(2t)
$$
Evaluate 
$y(t)$  for $t=0$

$$
\implies y(0) = c_1 + c_2 - \frac{15}{26}
$$
and 
$$
y(0)=\frac{1}{2}
$$
$$
\implies
c_1 + c_2 - \frac{15}{26} = 0.
$$
Differiate $y(t)$ and evaluate $y'(t)$ for $t=0$
```
derevative y(t) = c_1 Power[e,\(40)-3 t\(41)] + c_2 Power[e,\(40)-2 t\(41)] + Divide[3,26] sin(2 t) - Divide[15,26] cos(2 t) where t=0
```
https://www.wolframalpha.com/input/?i2d=true&i=derevative+y%5C%2840%29t%5C%2841%29+%3D+c_1+Power%5Be%2C%5C%2840%29-3+t%5C%2841%29%5D+%2B+c_2+Power%5Be%2C%5C%2840%29-2+t%5C%2841%29%5D+%2B+Divide%5B3%2C26%5D+sin%5C%2840%292+t%5C%2841%29+-+Divide%5B15%2C26%5D+cos%5C%2840%292+t%5C%2841%29+where+t%3D0

$$
   y'(0)=  -3 c_1 - 2 c_2 + \frac{3}{13}
$$
and
$$
y'(0) = 0
$$
$$
\implies
-3 c_1 - 2 c_2 + \frac{3}{13} = 0.
$$
Solve system of equations to find $c_1$ and $c_2$:

