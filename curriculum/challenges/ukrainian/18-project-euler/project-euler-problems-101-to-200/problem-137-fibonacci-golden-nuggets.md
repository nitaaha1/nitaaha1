---
id: 5900f3f51000cf542c50ff08
title: 'Завдання 137: золоті самородки Фібоначчі'
challengeType: 1
forumTopicId: 301765
dashedName: problem-137-fibonacci-golden-nuggets
---

# --description--

Розглянемо нескінченний поліноміальний ряд $A_{F}(x) = xF_1 + x^2F_2 + x^3F_3 + \ldots$, де $F_k$ є $k$-им членом у послідовності Фібоначчі: $1, 1, 2, 3, 5, 8, \ldots$. Таким чином $F_k = F_{k − 1} + F_{k − 2}, F_1 = 1$ та $F_2 = 1$.

Нас цікавлять значення $x$, за яких $A_{F}(x)$ є натуральним числом.

На диво,

$$\begin{align} A_F(\frac{1}{2}) & = (\frac{1}{2}) × 1 + {(\frac{1}{2})}^2 × 1 + {(\frac{1}{2})}^3 × 2 + {(\frac{1}{2})}^4 × 3 + {(\frac{1}{2})}^5 × 5 + \cdots \\\\
                 & = \frac{1}{2} + \frac{1}{4} + \frac{2}{8} + \frac{3}{16} + \frac{5}{32} + \cdots \\\\ & = 2 \end{align}$$

Відповідні значення $x$ для перших п’яти натуральних чисел наведено нижче.

| $x$                         | $A_F(x)$ |
| --------------------------- | -------- |
| $\sqrt{2} − 1$             | $1$      |
| $\frac{1}{2}$              | $2$      |
| $\frac{\sqrt{13} − 2}{3}$ | $3$      |
| $\frac{\sqrt{89} − 5}{8}$ | $4$      |
| $\frac{\sqrt{34} − 3}{5}$ | $5$      |

Назвемо $A_F(x)$ золотим самородком, якщо $x$ є раціональним, оскільки вони трапляються дедалі рідше. Наприклад, десятим золотим самородком є 74049690.

Знайдіть п’ятнадцятий золотий самородок.

# --hints--

`goldenNugget()` має повернути `1120149658760`.

```js
assert.strictEqual(goldenNugget(), 1120149658760);
```

# --seed--

## --seed-contents--

```js
function goldenNugget() {

  return true;
}

goldenNugget();
```

# --solutions--

```js
// solution required
```
