# Exercise 5

Let $\alpha = a + bi$ where $a, b \in \mathbb{R}$.

Let $\beta = (-a) + (-b)i$. We have $(-a), (-b) \in \mathbb{R}$ by the additive inverse property of $\mathbb{R}$.

Then,

```math
\begin{align*}
\alpha + \beta &= (a + bi) + ((-a) + (-b)i) \\
&= (a + -a) + (b + -b)i\ \ &&\text{ by definition of addition over } \mathbb{C} \\
&= 0 + 0i\ \ &&\text{ by additive inverse property of } \mathbb{R} \\
&= 0
\end{align*}
```

Thus, we have shown that $\exists \beta \in \mathbb{C}$ such that $\alpha + \beta = 0$. 

----

## Lemma

For any $\lambda \in \mathbb{C}$, $\alpha + 0 = \alpha$.

Let $\alpha = a + bi$ where $a, b \in \mathbb{R}$.

Then,

```math
\begin{align*}
\alpha + 0 &= (a + bi) + (0 + 0i)\ &&\text{ by definition of } \mathbb{R} \\
&= (a + 0) + (b + 0)i\ \ &&\text{ by definition of addition over } \mathbb{C} \\
&= a + bi\ \ &&\text{ by additive identity property of } \mathbb{R} \\
&= \alpha
\end{align*}
```

as desired.

----



Now, suppose $\exists \beta_1, \beta_2 \in \mathbb{C}$ such that $\alpha + \beta_1 = 0 = \alpha + \beta_2$

Then, we have

```math
\begin{align*}
\beta_1 &= \beta_1 + 0\  &&\text{ by the previous lemma } \\
&= \beta_1 + (\alpha + \beta_2)\ \ &&\text{ by definition of } \beta_2 \\
&= (\beta_1 + \alpha) + \beta_2\ \ &&\text{ by associativity } \mathbb{C} \\
&= (\alpha + \beta_1) + \beta_2\ \ &&\text{ by commutativity } \mathbb{C} \\
&= 0 + \beta_2\ \ &&\text{ by definition of } \beta_1 \\
&= \beta_2 + 0\ \ &&\text{ by commutativity } \mathbb{C} \\
&= \beta_2 &&\text{ by the previous lemma }
\end{align*}
```

Thus, we have shown that the $\beta \in \mathbb{C}$ such that $\alpha + \beta = 0$ is unique. 
