---
author:
- NONOGA Djintoba
date: 2026-01-03
title: Mathematical Concepts Presentation
---

::: frame
![image](logorudn.png){width="30%"}
:::

::: frame
Table of Contents
:::

# Introduction & Objectives

:::::: frame
Introduction & Objectives

::::: columns
::: column
0.7 **Presentation Goals:**

- Introduce fundamental set theory concepts

- Explain common mathematical sets

- Demonstrate calculus product rule

- Show practical applications

**Key Topics:**

- Sets and elements

- Special number sets ($\mathbb{N}$, $\mathbb{Z}$, $\mathbb{Q}$, $\mathbb{R}$)

- Derivative product rule
:::

::: column
0.3 ![image](logorudn.png){width="\\textwidth"}\
RUDN University\
Moscow, Russia
:::
:::::
::::::

# Set Theory Fundamentals

:::::: frame
Set Theory Fundamentals

::::: columns
::: column
0.48 **Basic Definitions:**

- Set: Collection of objects

- Example: $Z = \{\text{cow}, \text{pig}, \text{elephant}\}$

- Element: $\text{cow} \in Z$

- Common sets:

  - $\mathbb{N} = \{1,2,3,\ldots\}$ (Natural)

  - $\mathbb{Z} = \{\ldots,-2,-1,0,1,2,\ldots\}$ (Integer)

  - $\mathbb{Q} = \{p/q : p,q\in\mathbb{Z}, q\neq 0\}$ (Rational)

  - $\mathbb{R}$ = Decimal numbers (Real)
:::

::: column
0.48 **Set Operations:**

- Union: $A \cup B = \{x : x \in A \text{ or } x \in B\}$

- Intersection: $A \cap B = \{x : x \in A \text{ and } x \in B\}$

- Difference: $A \setminus B = \{x : x \in A \text{ and } x \notin B\}$

**Example:** If $A = \{1,2,3\}$ and $B = \{2,3,4\}$:

- $A \cup B = \{1,2,3,4\}$

- $A \cap B = \{2,3\}$

- $A \setminus B = \{1\}$
:::
:::::
::::::

# Calculus: Product Rule

:::::: frame
Calculus: Product Rule

::::: columns
::: column
0.65 **Product Rule Formula:** $$\frac{d}{dx}[f(x)g(x)] = f'(x)g(x) + f(x)g'(x)$$

**Example:** For $f(x) = x^2 \cdot \sin(x)$: $$\begin{align*}
            f'(x) &= \frac{d}{dx}(x^2) \cdot \sin(x) + x^2 \cdot \frac{d}{dx}(\sin(x)) \\
            &= 2x \cdot \sin(x) + x^2 \cdot \cos(x)
\end{align*}$$

**Proof Outline:**

- Start with definition: $f'(x) = \lim_{h\to 0} \frac{f(x+h)-f(x)}{h}$

- For $f(x) = g(x)h(x)$:

- Add and subtract $g(x+h)h(x)$

- Result: $f'(x) = g(x)h'(x) + g'(x)h(x)$
:::

::: column
0.35 ![image](example-image){width="80%"}\
Visual: Product rule

**Key Insight:** The derivative of a product is NOT the product of derivatives! $$(fg)' \neq f'g'$$
:::
:::::
::::::

# Applications & Conclusion

:::::: frame
Applications & Conclusion

::::: columns
::: column
0.7 **Applications:**

- **Physics:** Motion equations, force calculations

- **Engineering:** Signal processing, control systems

- **Computer Science:** Algorithms, machine learning

- **Economics:** Optimization, modeling

**Key Takeaways:**

1.  Sets provide foundation for mathematical structures

2.  Product rule is essential for calculus operations

3.  These concepts enable real-world problem solving
:::

::: column
0.3 ![image](logorudn.png){width="90%"}

**Thank You!**

Questions?

NONOGA Djintoba\
RUDN University
:::
:::::

------------------------------------------------------------------------

**References:** Calculus by James Stewart, Discrete Mathematics by Rosen
::::::
