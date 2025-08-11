# Trig Limits: Understanding the Why

**Name:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
**Date:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

---

## 1. The Two Fundamental Trig Limits

We will build and understand two special limits:

1. \$\lim\_{x \to 0} \frac{\sin x}{x} = 1\$
2. \$\lim\_{x \to 0} \frac{1 - \cos x}{x} = 0\$

---

## 2. Visualizing \$\frac{\sin x}{x}\$

The graph of \$y = \frac{\sin x}{x}\$ has a “hole” at \$x = 0\$, but as \$x \to 0\$ the function approaches 1.

**Observations:**

* The value is **undefined** at \$x = 0\$ because \$\frac{\sin 0}{0}\$ is \$\frac{0}{0}\$.
* As \$x\$ gets close to 0 from both sides, \$y\$ gets close to \_\_\_\_.

---

## 3. Why is \$\frac{\sin x}{x} \to 1\$?

**Geometric Idea:**

* Imagine a unit circle and a central angle \$x\$ (in radians).
* The arc length is \$x\$.
* The vertical coordinate of the point on the circle is \$\sin x\$.

From geometry:

$$
\sin x < x < \tan x
$$

Dividing by \$\sin x\$:

$$
1 < \frac{x}{\sin x} < \frac{1}{\cos x}
$$

Taking reciprocals and limits gives:

$$
\lim_{x \to 0} \frac{\sin x}{x} = 1
$$

---

## 4. Visualizing \$\frac{1 - \cos x}{x}\$

Observations:

* At \$x = 0\$, numerator \$= 0\$, denominator \$= 0\$ → indeterminate form.
* This expression is connected to the **Pythagorean identity**:

$$
\sin^2 x + \cos^2 x = 1
$$

---

## 5. Why is \$\frac{1 - \cos x}{x} \to 0\$?

From the half-angle identity:

$$
1 - \cos x = 2 \sin^2 \left( \frac{x}{2} \right)
$$

Then:

$$
\frac{1 - \cos x}{x} = \frac{2 \sin^2 \left( \frac{x}{2} \right)}{x}
$$

Factor one \$\sin \left( \frac{x}{2} \right)\$:

$$
= \frac{\sin \left( \frac{x}{2} \right)}{\frac{x}{2}} \cdot \sin \left( \frac{x}{2} \right)
$$

As \$x \to 0\$:

* \$\frac{\sin \left( \frac{x}{2} \right)}{\frac{x}{2}} \to 1\$
* \$\sin \left( \frac{x}{2} \right) \to 0\$

Therefore the limit is \_\_\_\_.

---

## 6. Example Problems

**Example 1:**

$$
\lim_{x \to 0} \frac{\sin(5x)}{x} = 5 \cdot 1 = 5
$$

**Example 2:**

$$
\lim_{x \to 0} \frac{\sin(7x)}{\sin(2x)} = \frac{7}{2}
$$

**Example 3:**

$$
\lim_{x \to 0} \frac{1 - \cos(4x)}{x} = 0
$$

---

## 7. Your Turn

1. \$\lim\_{x \to 0} \frac{\sin(3x)}{x}\$
2. \$\lim\_{x \to 0} \frac{\sin(5x)}{\sin(2x)}\$
3. \$\lim\_{x \to 0} \frac{1 - \cos(6x)}{x}\$

---

## 8. Key Takeaways

* **Memorize**: \$\lim\_{x \to 0} \frac{\sin x}{x} = 1\$, \$\lim\_{x \to 0} \frac{1 - \cos x}{x} = 0\$
* Understand **why** they are true from geometry, not just from algebra.
* Use these to simplify more complicated limits involving trig functions.
