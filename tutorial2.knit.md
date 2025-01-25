---
title: "Tutorial 2: OLS and first repliction"
format: html
editor: visual
toc: true
toc-title: ""
toc-location: right
---

::: {.cell}

:::




We are going to dig into into the workhorse model in macroeconomics: the Solow model.

## Quick model summary

1.  **Production Function**: The economy produces output using a production function of the form: $$ Y_t = F(K_t, L_t) $$ where $Y$ is output, $K$ is capital, and $L$ is labor. Often, a Cobb-Douglas production function is assumed: $$ Y_t = K_t^\alpha L_t^{1-\alpha} $$ where $0 < \alpha < 1$. Capital comes at price $r$ and labor comes at price $w$.

2.  **Constant Returns to Scale**: Doubling the inputs (capital and labor) doubles the output.

3.  **Diminishing Returns**: Increasing one input, holding the other constant, leads to smaller and smaller increases in output.

4.  **Exogenous Saving Rate**: A fixed fraction $s$ of output is saved and invested.

5.  **Capital Depreciation**: A constant fraction $\delta$ of capital depreciates each period.

6.  **Population Growth**: The labor force grows at a constant rate $n$.

7.  **Technological Progress**: Technology improves at an exogenous rate $g$, increasing productivity over time.

8.  **Steady State**: In the long run, the economy reaches a steady state where capital per worker ($k$) and output per worker ($y$) are constant.

## Exercises

### 1. Warm-up: Return to scale

Let $\lambda \in (0,1)$, if $F(\lambda X, \lambda Y) < \lambda F(X,Y)$, the function has decreasing return to scales (and increasing for $>$). If $F(\lambda X, \lambda Y) = \lambda F(X,Y)$, the function has constant return to scale. For the following functions, state if they exhibit positive, constant, or negative return to scale.

1.  $y_1 = 10x^2y^2$
2.  $y_2 = \frac{1}{2}x^{1/3}y^{1/2}$
3.  $y_3 = x + 2y$
4.  $y_4 = \sqrt{x} + \log(y)$

### 2. Solve the maximization problem

1.  Show that if $x=0$ and/or $y=0$ production does not occur
2.  Show that marginal productivity is positive for capital and wage
3.  Show that marginal productivity is decreasing for capital and wage
4.  Write the down the profit maximization program
5.  Solve the program

### 3. Per worker term

Denote $y=Y/L$, the per-worker production, and $k=K/L$ the per-worker capital.

1.  Show that $y=Ak^\alpha$

### 4. Capital accumulation

Capital accumulation is given by $\dot K=sY-\delta K$.

1.  Interpret this equation
2.  Show that $\frac{\dot K}{K} = s\frac{y}{k}-\delta$
3.  Show that $\dot k = sAk^\alpha - (\delta - n)k$
4.  What happen if $sAk^\alpha > (\delta - n)k$ ?

### 5. Steady state

A steady-state is a capital stock per capita $k^\star$ where, when reached, $\dot k = 0$.

1.  What is the steady-state level of output per capita $y^\star$ ?
2.  Interpret

### 6. Comparative statics

Comparative statics exercises are thought experiment in which we change the value of a parameter and compare the past and new equilibrium. Consider a new saving rate $s'>s$.

1.  How does capital accumulation change?
2.  How does change the steady-state capital stock?
3.  How does change the stead-state level of output per capita?

### 7. Balanced growth path \[Bonus\]

The balanced growth path is a situation during which capital per worker and output per worker grow a constant (but potentially different) rates. The steady state is a BGP with zero growth rate. Denote $g_y$ and $g_k$ the capital and output per worker growth rates .

1.  Show that $g_y=g_k$

