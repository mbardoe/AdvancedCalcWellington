% Day 2 Notes: The 0/0 Mystery and Approximating Limits
% Name: __________________________
% Date: __________________________

---

## 1. The 0/0 Mystery

Today’s goal: Understand why \( \frac{0}{0} \) is not just “undefined,” but a **mystery** that requires deeper investigation.

**Example:**
\[
\lim_{x \to 2} \frac{x^2 - 4}{x - 2}
\]

If we **plug in** \( x = 2 \) directly:

Numerator: \( 2^2 - 4 = \_\_\_\_ \)  
Denominator: \( 2 - 2 = \_\_\_\_ \)  

Result: \( \frac{0}{0} \) → **This is called an ____________ form**.

---

**Fill-in-the-blank:**
- \( \frac{0}{0} \) means **the top and bottom both go to zero** as \( x \) approaches the point.
- We can’t stop here — we must **look closer** to see what value the function is approaching.

---

## 2. Using a Table of Values

We’ll choose \( x \)-values **close to** (but not equal to) the mystery point.

**Example Table:** \( f(x) = \frac{x^2 - 4}{x - 2} \)

| \(x\)    | \(f(x)\)  |
|----------|-----------|
| 1.9      |           |
| 1.99     |           |
| 1.999    |           |
| 2.001    |           |
| 2.01     |           |
| 2.1      |           |

---

**Questions:**
1. As \( x \) approaches 2 from the **left**, \( f(x) \) gets closer to \_\_\_\_\_.
2. As \( x \) approaches 2 from the **right**, \( f(x) \) gets closer to \_\_\_\_\_.
3. Therefore:
\[
\lim_{x \to 2} \frac{x^2 - 4}{x - 2} = \_\_\_\_\_
\]

---

## 3. Finding an Equivalent Representation

Many times, there is an **equivalent function** that agrees with the original everywhere except at the mystery point.  
If we can rewrite the function into this simpler form, the limit is easier to evaluate.

We can factor the numerator:
\[
x^2 - 4 = \_\_\_\_\_ \times \_\_\_\_\_
\]

Cancelling the common factor (except at \( x = 2 \)) shows:
\[
f(x) = \_\_\_\_\_
\]
for \( x \neq 2 \).

This **simplified form** lets us evaluate the limit **without making a table**.

---

**Key Idea:**
- Tables show **what** is happening.  
- Algebra shows **why** it’s happening.

---

## 4. Your Turn

Find the limit by making a table of values, then by simplifying algebraically.

\[
\lim_{x \to 1} \frac{x^2 - 1}{x - 1}
\]

**Table Method:**

| \(x\)    | \(f(x)\)  |
|----------|-----------|
| 0.9      |           |
| 0.99     |           |
| 0.999    |           |
| 1.001    |           |
| 1.01     |           |
| 1.1      |           |

**Algebraic Method:**

Factor:
\[
x^2 - 1 = \_\_\_\_\_ \times \_\_\_\_\_
\]
Simplify:
\[
f(x) = \_\_\_\_\_
\]
Limit:
\[
\lim_{x \to 1} f(x) = \_\_\_\_\_
\]

---

## 5. Warnings About Tables

- Tables can suggest a limit, but may be misleading if:
  - The function oscillates near the point.
  - Rounding errors in calculations distort results.
  - Values chosen are not close enough to the target point.

**Notes:**
\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

---
