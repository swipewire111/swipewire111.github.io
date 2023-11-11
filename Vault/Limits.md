#flashcards 
___

### limits-
limits are the defining factor, that distinguish the fields of calculus from algebra and trigonometry
What are limits used to describe :: Limits are used to describe an infinitesimal change of a value, IE: it describes extremely minute changes in a value
Informal description of limits :: Limits are the neighborhood of values around the value $a$ , which might be infinitesimally larger or smaller than $a$ but is never equal to $a$
<!--SR:!2023-08-01,14,250-->
$\lim_{x\to a}f(x) =l$  here, what is "$l$" :: Here $l$ is called the limiting value of the function, where as '$x$' approaches arbitrarily close to the value '$a$', the value of $f(x)$ approaches arbitrarily close to the value of $l$
`special property about a`::`a need not be a number in the domain of f`
<!--SR:!2023-07-15,4,270-->
k
considering the function $f(x)=\frac{x}{x}$ where $\lim_{x\to0}$ is equal to one, as the function is defined for all values that are not 0, where $\frac{0}{0}$ is indeterminate 

---
### Concept of infinity
- infinity :: Although $\infty$ means nothing by itself, when a number approaches infinity, it means that it approaches an arbitrarily large value, but no number can be equal to infinity due to the fact that infinity has no actual value and $n=\infty$ is a meaningless statement.
<!--SR:!2023-07-15,4,270-->
-  Approaching infinity :: When a number is said to approach infinity, or $\lim_{x\to\infty}$ that means that it gains this arbitrarily large value, that cannot be given a finite value
<!--SR:!2023-10-04,67,290-->

---
### Oscillating functions
-  When a function tends to neither $\infty$ or $-\infty$ we say that as $n\to\infty$ , $f(n)$ oscillates 

---
### Bounded functions
-  A functions is said to be bounded when :: The function $f(x)=y$ lies in between two values, shown as $B\leq f(x), y\leq A$ where  the graph of the function will always lie in between the lines of $y=B$ and $y=A$ 
<!--SR:!2023-08-10,23,250-->
-  The formal definition of a bounded function :: The formal definition of a bounded function is that, for a given function $f(x)$ for $x\to a$ There exists a neighborhood around the value $a$ for which the function is bound.
<!--SR:!2023-07-14,3,250-->
---
### Theorems on limits
$\lim_{x\to a}b=$ :: $b$
$\lim_{x\to a}x=$ :: $a$
$\lim_{x\to a}x^n =$ :: $a^n$
<!--SR:!2023-10-05,68,290-->

#### The constant multiple rule
-   $\lim_{x\to a}k(f(x)) =$:: $k\lim_{x\to a}f(x)$, where $k$ is independent of the limit, you may take a constant outside of a limit.

#### The sum rule

-  $\lim_{x\to a}[f(x)+g(x)] =$ :: $\lim_{x\to a} f(x)+ \lim_{x \to a}g(x)$ IE, the limit of the sum of two functions is equal to the sum of their limits.
<!--SR:!2023-07-15,4,270-->
#### The Difference rule
-  $\lim_{x\to a}[f(x)-g(x)] =$ :: $\lim_{x\to a} f(x)-\lim_{x \to a}g(x)$ where the limit of the difference of two function is equal to the difference of the limits
<!--SR:!2023-07-15,4,270-->

#### The Product rule
- $\lim_{x\to a}f(x)g(x)=$::$\lim_{x\to a}f(x)\lim_{x\to a}g(x)$ 
<!--SR:!2023-07-15,4,270-->

#### The Quotient rule
-  $\lim_{x\to a}\frac{f(x)}{g(x)} =$::$\frac{\lim_{x\to a}f(x)}{\lim_{x\to a}g(x)}$
<!--SR:!2023-08-12,25,290-->

#### Limits on logarithm
-  $\lim_{x\to a}\log(f(x))=$ :: $\log[\lim_{x\to a}f(x)]$
<!--SR:!2023-07-15,4,270-->

#### For exponents
- $\lim_{x\to a}e^{f(x)}=$ :: $e^{\lim_{x\to a}f(x)}$

#### for inequalities
-  for $f(x)\geq g(x)$ for all values of x, besides a:: $\lim_{x\to a}f(x)\geq \lim_{x\to a}g(x)$
<!--SR:!2023-07-15,4,270-->

#### For modulus
-  $\lim_{x\to a}|f(x)|=$::$|\lim_{x\to a}f(x)|$

#### For limits that approach infinity
-  $\lim_{x\to a}f(x)=\infty$ or $-\infty$ then$\frac{1}{f(x)}=$ :: $0$
<!--SR:!2023-10-05,68,290-->

#### For linear equations
-  $\lim_{x\to a}mx+c=$::$ma+c$
<!--SR:!2023-07-15,4,270-->

#### For exponents
-  $\lim_{x\to a}[f(x)]^n=$::$[\lim_{x\to a}[f(x)]]^n$

---
### Expansions of some functions
$e^x$::$1+\frac{x}1+\frac{x^2}{2!}+.....\frac{x^n}{n!}$   
$sin(x)$::$x-\frac{x^3}{3!}+\frac{x^5}{5!}+....(-1)^n\frac{x^{2n+1}}{(2n+1)!}$
$cos(x)$ :: $1-\frac{x^2}{2!}+\frac{x^4}{4!}+.....(-1)^n\frac{x^{2n}}{(2n)!}$
<!--SR:!2023-09-25,58,250-->
$tan(x)$ :: $x+\frac{x^3}{3}+\frac{2x^5}{15}......$
$sinh$:: $x +\frac{x^3}{3!}+\frac{x^5}{5!}+....\frac{x^{2n+1}}{(2n+1)!}$
<!--SR:!2023-09-23,56,250-->
$cosh$ :: $1+x+\frac{x^2}{2!}+\frac{x^4}{4!}+....\frac{x^{2n}}{(2n)!}$
<!--SR:!2023-10-07,70,290-->
$\ln(1+x)$ :: $x-\frac{x^2}{2}+\frac{x^3}{3}-\frac{x^4}{4}+....(-1)^{n+1}\frac{x^n}{n}$ for $-1<x\leq 1$
$\ln(1-x)$ :: $-[x+\frac{x^2}{2}+\frac{x^3}{3}+\frac{x^4}{4}+...\frac{x^n}{n}]$ for $-1 \leq x < 1$
<!--SR:!2023-07-20,2,250-->
$\tan^{-1}$ :: $x-\frac{x^3}{3}+\frac{x^5}{5}-\frac{x^7}{7}....(-1)^{n+1}\frac{x^{2n+1}}{2n+1}$ for $-1<x<1$
$\sin^{-1}$ :: $$ 
<!--SR:!2023-09-24,57,250-->