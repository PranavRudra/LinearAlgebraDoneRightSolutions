# Exercise 6

Let $\alpha = a + bi$ where $a, b \in \mathbb{R}$.

Let 

$$\beta = \frac{a}{a^2 + b^2} + \frac{(-b)i}{a^2 + b^2}$$

and observe that 

$$\frac{a}{a^2 + b^2},\  \frac{-b}{a^2 + b^2} \in \mathbb{R}$$

by the closure of $\mathbb{R}$ under addition and multiplication. Thus, $\beta \in \mathbb{C}$. 

Now, we have

```math
\begin{align*}
\alpha(\beta) &= (a + bi)\left(\frac{a}{a^2 + b^2} + \frac{(-b)i}{a^2 + b^2}\right) \\
&= \left(\frac{(a + bi)(a - bi)}{a^2 + b^2}\right) \\
&= \frac{(a^2 - (b \cdot -b)) + ((a \cdot -b) + (ba))i}{a^2 + b^2}\ \ &&\text{ by definition of multiplication over } \mathbb{C} \\
&= \frac{(a^2 - (b \cdot -b)) + (a(-b + b))i}{a^2 + b^2}\ \ &&\text{ by distributive property of } \mathbb{R} \\
&= \frac{(a^2 - (b \cdot -b)) + (a(0))i}{a^2 + b^2}\ \ &&\text{ by additive identity property of } \mathbb{R} \\
&= \frac{(a^2 - (b \cdot -b)) + 0i}{a^2 + b^2}\ \ &&\text{ by zero multiplication property of } \mathbb{R} \\
&= \frac{(a^2 - (b \cdot -b))}{a^2 + b^2}\ \ &&\text{ by definition of } \mathbb{R} \\
&= \frac{a^2 + b^2}{a^2 + b^2} \\
&= 1
\end{align*}
```

Thus, we have shown by construction that $\exists \beta \in \mathbb{C}$ such that $\alpha(\beta) = 1$. 

----

## Lemma

For any $\lambda \in \mathbb{C}$, $\alpha(1) = \alpha$.

Let $\alpha = a + bi$ where $a, b \in \mathbb{R}$.

Then,

```math
\begin{align*}
\alpha(1) &= (a + bi)(1 + 0i)\ &&\text{ by definition of } \mathbb{R} \\
&= (a(1) - b(0)) + (a(0) + b(1))i\ \ &&\text{ by definition of multiplication over } \mathbb{C} \\
&= (a(1) + 0) + (0 + b(1))i\ \ &&\text{ by zero multiplication property of } \mathbb{R} \\
&= a(1) + b(1)i\ \ &&\text{ by additive identity property of } \mathbb{R} \\
&= a + bi\ \ &&\text{ by multiplicative identity property of } \mathbb{R} \\
&= \alpha
\end{align*}
```

as desired. 

----
