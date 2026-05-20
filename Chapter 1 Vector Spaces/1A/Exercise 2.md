# Exercise 2

Let $\alpha = a + bi$ where $a, b \in \mathbb{R}$.

Let $\beta = c + di$ where $c, d \in \mathbb{R}$.

Let $\lambda = e + fi$ where $e, f \in \mathbb{R}$.

Then,

```math
\begin{align*}
(\alpha + \beta) + \lambda &= ((a + bi) + (c + di)) + (e + fi) \\
&= ((a + c) + (b + d)i) + (e + fi)\ \ &&\text{ by definition of addition over } \mathbb{C} \\
&= ((a + c) + e) + ((b + d) + f)i\ \ &&\text{ by definition of addition over } \mathbb{C} \\
&= (a + (c + e)) + (b + (d + f))i\ \ &&\text{ by associativity of addition over } \mathbb{R} \\
&= (a + bi) + ((c + e) + (d + f)i)\ \ &&\text{ by definition of addition over } \mathbb{C} \\
&= (a + bi) + ((c + di) + (e + fi))\ \ &&\text{ by definition of addition over } \mathbb{C} \\
&= \alpha + (\beta + \lambda)
\end{align*}
```
