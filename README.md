# cheat-sheet

## Design Principles

- Notation prioritizes semantic content over symbolic compactness.
- 
  
---

**Convention.** Each formula is presented as a canonical representative of its equivalence class.

---

# Part I Foundations

## Set Theory 
### Basic Concepts
#### Operations
##### Unions and Intersections
###### De Morgan's Laws
### Relations and Functions 
### Cardinality 
#### Countable and Uncountable Sets
## Logic
### Propositional Logic
### Predicate Logic
### Proof Systems
#### Induction
### Model Theory

# Part II Algebra

## Elementary Algebra
### Numbers and Operations
#### Complex Numbers
##### Euler's Identity
### Polynomials
#### Roots
##### Fundamental Theorem of Algebra
###### Complex Conjugate Roots
## Linear Algebra
### Vectors and Spaces
### Matrices and Determinants
#### Matrix Operations
##### Multiplication
###### Non-commutativity
#### Rank and Nullity
### Linear Transformations
### Eigenvalues and Eigenvectors
#### Spectral Theorem
## Abstract Algebra
### Groups
#### Geometric and Combinatorial Group Theory
### Rings
### Fields
### Galois Theory
### Representation Theory
#### Character Theory
## Category Theory
### Categories, Functors, and Natural Transformations
### Limits and Colimits
### Adjunctions
## Number Theory
### Divisibility
#### Euclidean Algorithm
#### Diophantine Equations
### Primes
#### Distribution of Primes
### Modular Arithmetic
#### Chinese Remainder Theorem
### Algebraic Number Theory
### Analytic Number Theory
### Computational Number Theory
### Applications
#### Cryptography (RSA, Diffie-Hellman)

# Part III Analysis

## Calculus
### Limits and Continuity
#### The Limit Laws
#### Epsilon-Delta Definition
#### Continuity and Discontinuity
### Differential Calculus
#### Derivatives
##### Chain Rule
###### Higher Order Derivatives
#### Mean Value Theorem
### Integral Calculus
#### Riemann Sums
#### Fundamental Theorem of Calculus
### Sequences and Series
#### Convergence Tests
#### Taylor and Maclaurin Series
## Multivariable and Vector Calculus
### Partial Derivatives
### Vector Fields
#### Gradient, Divergence, and Curl
### Line and Surface Integrals
#### Stokes' Theorem and Divergence Theorem
## Real Analysis
### Metric Spaces
### Continuity and Convergence
### Measure Theory
## Complex Analysis
### Analyticity
#### Cauchy-Riemann Equations
### Residues
## Fourier Analysis
### Fourier Series
### Fourier Transforms
### Harmonic Analysis
## Functional Analysis
### Hilbert and Banach Spaces
### Operator Theory
## Differential Equations
### Ordinary Differential Equations (ODEs)
### Partial Differential Equations (PDEs)
## Dynamical Systems

# Part IV Geometry

## Euclidean Geometry
### Plane Geometry (2D)
#### Polygons
#### Curves
### Solid Geometry (3D)
#### Polyhedra
#### Curved Solids
## Analytic Geometry
### Coordinate Systems

* Equations of a line

  * Slope–Intercept Form

  $$
  y = \text{(slope)}x + \text{(y-intercept)}
  $$

  * Point–Slope Form

  $$
  y - y_1 = \text{(slope)}(x - x_1), \\quad P = (x_1,y_1)
  $$

  * Two–Point Form

  $$
  y - y_1 = \frac{y_2 - y_1}{x_2 - x_1}(x - x_1), \\quad P_1 = (x_1,y_1) \text{ and } P_2 = (x_2,y_2)
  $$


  * Standard (General) Form

  $$
  Ax + By + C = 0
  $$

  * Intercept Form

  $$
  \frac{x}{a} + \frac{y}{b} = 1
  $$

  * Symmetric Form (2D)

  $$
  \frac{x - x_1}{a} = \frac{y - y_1}{b}
  $$

  * Parametric Form

  $$
  \begin{cases}
  x = x_0 + at \\
  y = y_0 + bt
  \end{cases}
  $$

  * Vector Form

  $$
  \mathbf{r}(t) = \mathbf{r}_0 + t\mathbf{v}
  $$

  $$
  \begin{pmatrix}
  x \\
  y
  \end{pmatrix}
  = \begin{pmatrix}
  x_0 \\
  y_0
  \end{pmatrix} + t \begin{pmatrix}
  a \\
  b
  \end{pmatrix}
  $$

  * Normal (Hesse) Form

  $$
  x \cos \theta + y \sin \theta = p
  $$
  
### Conic Sections
## Algebraic Geometry
### Affine and Projective Varieties
### Schemes and Sheaves
## Arithmetic Geometry
### Moduli Spaces
## Differential Geometry
### Manifolds
### Riemannian Geometry
#### Metric Tensors
##### Curvature (Ricci, Riemann)
## Topology
### Point-Set Topology
#### Compactness and Connectedness
### Algebraic Topology
#### Fundamental Groups (Homotopy)
#### Homology and Cohomology
#### Betti Numbers
### Differential Topology
#### Smooth Manifolds
#### Transversality and Cobordism
## High-Dimensional and Probabilistic Geometry
### Concentration of Measure

# Part V Discrete Mathematics

## Combinatorics
### Counting Principles
### Generating Functions
### Enumerative Combinatorics
### Algebraic Combinatorics
### Extremal Combinatorics
### Probabilistic Combinatorics
## Graph Theory
### Connectivity
### Paths and Cycles
### Trees and Spanning Trees
## Discrete Structures
### Posets and Lattices

# Part VI Applied Mathematics

## Probability and Statistics
### Probability Theory
#### Bayesian vs Frequentist
### Statistics
### Stochastic Processes
## Numerical Analysis
### Root Finding
### Numerical Linear Algebra
## Operations Research
### Linear Programming
### Game Theory
### Mathematical Modeling












## Equations of a line

Slope–Intercept Form

$$
y = \text{(slope)}x + \text{(y-intercept)}
$$

Point–Slope Form

$$
y - y_1 = \text{(slope)}(x - x_1), \\quad P_1 = (x_1,y_1)
$$

Two–Point Form

$$
y - y_1 = \frac{y_2 - y_1}{x_2 - x_1}(x - x_1), \\quad P_1 = (x_1,y_1) \text{ and } P_2 = (x_2,y_2)
$$


Standard (General) Form

$$
Ax + By + C = 0
$$

Intercept Form

$$
\frac{x}{a} + \frac{y}{b} = 1
$$

Symmetric Form (2D)

$$
\frac{x - x_1}{a} = \frac{y - y_1}{b}
$$

Parametric Form

$$
\begin{cases}
x = x_0 + at \\
y = y_0 + bt
\end{cases}
$$

Vector Form

$$
\mathbf{r}(t) = \mathbf{r}_0 + t\mathbf{v}
$$

explicitly,

$$
\begin{pmatrix}
x \\
y
\end{pmatrix}
= \begin{pmatrix}
x_0 \\
y_0
\end{pmatrix} + t \begin{pmatrix}
a \\
b
\end{pmatrix}
$$

Normal (Hesse) Form

$$
x\cos\theta + y\sin\theta = p
$$

## Pythagorean Theorem

$$
\text{(first leg)}^2 + \text{(second leg)}^2 = \text{(hypotenuse)}^2
$$

$$
\text{distance between 2 points} = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2}
$$

## Multiplication table

| ×  | 3  | 4  | 5  | 6  | 7  | 8  | 9  | 10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | 20 |
|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|
| 2  |    |    |    |    |    |    |    |    |    | 24 | 26 | 28 | 30 | 32 | 34 | 36 | 38 |    |
| 3  |    |    |    |    |    |    |    |    |    | 36 | 39 | 42 | 45 | 48 | 51 | 54 | 57 |    |
| 4  |    |    |    |    |    |    |    |    |    | 48 | 52 | 56 | 60 | 64 | 68 | 72 | 76 |    |
| 5  |    |    |    |    |    |    |    |    |    | 60 | 65 | 70 | 75 | 80 | 85 | 90 | 95 |    |
| 6  |    |    |    |    |    |    |    |    |    | 72 | 78 | 84 | 90 | 96 | 102 | 108 | 114 |     |
| 7  |    |    |    |    |    |    |    |    |    | 84 | 91 | 98 | 105 | 112 | 119 | 126 | 133 |     |
| 8  |    |    |    |    |    |    |    |    |    | 96 | 104 | 112 | 120 | 128 | 136 | 144 | 152 |     |
| 9  |    |    |    |    |    |    |    |    |    | 108 | 117 | 126 | 135 | 144 | 153 | 162 | 171 |     |
| 10 |    |    |    |    |    |    |    |    |    | 120 | 130 | 140 | 150 | 160 | 170 | 180 | 190 |     |
| 11 |    |    |    |    |    |    |    |    |    | 132 | 143 | 154 | 165 | 176 | 187 | 198 | 209 |     |
| 12 | 36 | 48 | 60 | 72 | 84 | 96 | 108 |    | 132 | 144 |    |    |    |    |    |    |    |    |
| 13 | 39 | 52 | 65 | 78 | 91 | 104 | 117 |    | 143 |    | 169 |    |    |    |    |    |    |    |
| 14 | 42 | 56 | 70 | 84 | 98 | 112 | 126 |    | 154 |    |    | 196 |    |    |    |    |    |    |
| 15 | 45 | 60 | 75 | 90 | 105 | 120 | 135 |    | 165 |    |    |    | 225 |    |    |    |    |    |
| 16 | 48 | 64 | 80 | 96 | 112 | 128 | 144 |    | 176 |    |    |    |    | 256 |    |    |    |    |
| 17 | 51 | 68 | 85 | 102 | 119 | 136 | 153 |    | 187 |    |    |    |    |    | 289 |    |    |    |
| 18 | 54 | 72 | 90 | 108 | 126 | 144 | 162 |    | 198 |    |    |    |    |    |    | 324 |    |    |
| 19 | 57 | 76 | 95 | 114 | 133 | 152 | 171 |    | 209 |    |    |    |    |    |    |    | 361 |    |
| 20 | 60 | 80 | 100 | 120 | 140 | 160 | 180 |    | 220 |    |    |    |    |    |    |    |    | 400 |



## Derivatives

$$
(x^n)' = n x^{n-1}
$$

$$
(\sin x)' = \cos x
$$

$$
(\cos x)' = -\sin x
$$

$$
(\tan x)' = \sec^2 x
$$

$$
(e^x)' = e^x
$$

$$
(\ln x)' = \frac{1}{x}
$$

$$
(a^x)' = a^x \ln a
$$

$$
(\sqrt{x})' = \frac{1}{2\sqrt{x}}
$$

$$
(uv)' = u'v + uv'
$$

$$
\left(\frac{u}{v}\right)' = \frac{u'v - uv'}{v^2}
$$

## Geometry — Areas

$$\text{area(triangle)} = \frac12 \cdot \text{base} \cdot \text{height}$$

$$\text{area(circle)} = \pi \cdot \text{radius}^2$$

$$
\begin{aligned}
\text{area(triangle)} &= \frac12 \cdot \text{base} \cdot \text{height} \\
\text{area(circle)} &= \pi \cdot \text{radius}^2 \\
\text{area(rectangle)} &= \text{width} \cdot \text{height}
\end{aligned}
$$


## Geometry — Areas

$$
\begin{aligned}
\text{area}(\text{triangle}) &= \frac12 \cdot \text{base} \cdot \text{height} \\
\text{area}(\text{circle}) &= \pi \cdot \text{radius}^2 \\
\text{area}(\text{rectangle}) &= \text{width} \cdot \text{height}
\end{aligned}
$$

## Volumes

$$\text{volume}(\text{cube}) = s^3$$

$$\text{volume}(\text{cylinder}) = \pi r^2 h$$

$$\text{volume}(\text{sphere}) = \frac{4}{3}\pi r^3$$

## Exponent Laws

$$
\begin{aligned}
a^m \cdot a^n &= a^{m+n} \\
\frac{a^m}{a^n} &= a^{m-n} \\
(a^m)^n &= a^{mn} \\
(ab)^n &= a^n b^n \\
\left(\frac{a}{b}\right)^n &= \frac{a^n}{b^n}
\end{aligned}
$$

## Exponent Laws

$$
\begin{aligned}
(1)\quad a^m \cdot a^n &= a^{m+n} \\
(2)\quad \frac{a^m}{a^n} &= a^{m-n} \\
(3)\quad (a^m)^n &= a^{mn}
\end{aligned}
$$



## Volume

$$
\begin{aligned}
\text{cube} &: s^3 \\
\text{cylinder} &: \pi r^2 h \\
\text{sphere} &: \frac{4}{3}\pi r^3 \\
\text{pyramid} &: \frac13 \cdot \text{base area} \cdot h
\end{aligned}
$$

## Exponent Laws

1. $$a^m \cdot a^n = a^{m+n}$$
2. $$\frac{a^m}{a^n} = a^{m-n}$$
3. $$(a^m)^n = a^{mn}$$

## Vector Space Axioms

1. $$u + v = v + u$$
2. $$(u + v) + w = u + (v + w)$$
3. $$\exists 0: v + 0 = v$$

## Gaussian Elimination

1. Swap rows.
2. Multiply a row by a scalar.
4. Add a multiple of one row to another.

5. 1. $$\text{area(triangle)} = \frac12 bh$$
2. $$\text{area(circle)} = \pi r^2$$
3. $$\text{area(rectangle)} = wh$$

## a

$$a^m a^n = a^{m+n}$$
$$\frac{a^m}{a^n} = a^{m-n}$$
$$(a^m)^n = a^{mn}$$

$$
\begin{aligned}
a^m a^n &= a^{m+n} \\
\frac{a^m}{a^n} &= a^{m-n} \\
(a^m)^n &= a^{mn}
\end{aligned}
$$

---

factoring formulas

radical rules

exponent rules

log rules

quadratic formula

binomial theorem

area

volume

pythagoras theorem

fundamental theorem

trig identities

trig definitions

angle sum

limits

deruvatives

integrals

determinand 2x2

determinant 3x3

inverse 2x2 

taylor series

geometric series

probability density functions




---


[Design Principles](#design-principles)


---

# Markdown syntax guide

## Lists

### Unordered

* Item 1
* Item 2
* Item 2a
* Item 2b
    * Item 3a
        * Item 3 a a
            * Item 3 a a
    * Item 3b

### Ordered

1. Item 1
2. Item 2
3. Item 3
    1. Item 3a
    2. Item 3b

## Headers

# This is a Heading h1
## This is a Heading h2
###### This is a Heading h6

## Emphasis

*This text will be italic*  
_This will also be italic_

**This text will be bold**  
__This will also be bold__

_You **can** combine them_



## Images

![This is an alt text.](/image/Markdown-mark.svg "This is a sample image.")

## Links

You may be using [Markdown Live Preview](https://markdownlivepreview.com/).

## Blockquotes

> Markdown is a lightweight markup language with plain-text-formatting syntax, created in 2004 by John Gruber with Aaron Swartz.
>
>> Markdown is often used to format readme files, for writing messages in online discussion forums, and to create rich text using a plain text editor.

## Tables

| Left columns  | Right columns |
| ------------- |:-------------:|
| left foo      | right foo     |
| left bar      | right bar     |
| left baz      | right baz     |

## Blocks of code

```
let message = 'Hello world';
alert(message);
```

## Inline code

This web site is using `markedjs/marked`.
