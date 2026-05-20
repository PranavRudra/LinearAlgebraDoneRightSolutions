# Exercise 3

Let $\alpha = a + bi$ where $a, b \in \mathbb{R}$.

Let $\beta = c + di$ where $c, d \in \mathbb{R}$.

Let $\lambda = e + fi$ where $e, f \in \mathbb{R}$.

Then,

```math
\begin{align*}
(\alpha\beta)\lambda &= ((a + bi)(c + di))(e + fi) \\
&= ((ac - bd) + (ad + bc)i)(e + fi)\ \ &&\text{ by definition of multiplication over } \mathbb{C} \\
&= ((e(ac - bd)) - (f(ad + bc))i) + ((f(ac - bd)) + (e(ad + bc)))i\ \ &&\text{ ... } \\
&= \cdots \\
&= (a + bi)((ce - df) + (de + cf)i)\ \ &&\text{ ... } \\
&= (a + bi)((c + di)(e + fi))\ \ &&\text{ by definition of multiplication over } \mathbb{C} \\
&= \alpha(\beta\lambda)
\end{align*}
```
