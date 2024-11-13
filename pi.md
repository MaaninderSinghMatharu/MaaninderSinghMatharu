# Determining the Approximate Value of π (Pi) Using Discretization Approach

### Objectives:

1. Understand the application of the finite element method (FEM) in approximating the value of π.
2. Derive expressions for the upper and lower bounds of π using geometric properties of inscribed and circumscribed polygons.
3. Calculate and compare these bounds for different numbers of sides (N) of the polygons.
4. Visualize the results to understand how increasing the number of sides affects the bounds.

---

## Explanation:

The task of approximating π can be achieved by discretizing a circle using regular polygons. By inscribing and circumscribing polygons around a circle, we can estimate upper and lower bounds for π. This approach is rooted in ancient techniques and forms the basis of modern numerical methods like the finite element method (FEM), which breaks down complex, continuous shapes into discrete elements to approximate solutions.

### Understanding the Discretization Approach:

In this method:
- An **inscribed polygon** (one inside the circle) gives a **lower bound** of π, as its perimeter is less than the circumference of the circle.
- A **circumscribed polygon** (one outside the circle) gives an **upper bound** of π, as its perimeter is greater than the circle’s circumference.

As the number of sides $N$ of the polygon increases, both the inscribed and circumscribed polygons become closer approximations of the circle. This reduces the gap between the upper and lower bounds of π.

---

### Deriving the Bounds:

Archimedes Method of Exhaustion has been used to derive these formulas, follow the link given below in which the derivation has been explained beautifully.

[ARCHIMEDES EXHAUSTION METHOD EXPLAINED](https://youtu.be/DLZMZ-CT7YU?feature=shared)

For a circle of unit radius, $r = 1$:
- The circumference $C$ of the circle is $\pi$.
- For a regular polygon with $N$ no. of sides, we can derive the following formulas:

#### Lower Bound (Inscribed Polygon):
The perimeter of an inscribed polygon with $N$ sides can be calculated as:

$$\pi_{\text{inscribed}} = N \cdot \sin\left(\frac{180}{N}\right)$$

#### Upper Bound (Circumscribed Polygon):
The perimeter of a circumscribed polygon with $N$ sides can be calculated as:

$$\pi_{\text{circumscribed}} = N \cdot \tan\left(\frac{180}{N}\right)$$

These formulas yield the lower and upper bounds for π.

---

### Calculation of Bounds:

Let's calculate the bounds for polygons with $N = 3$ (triangle), $N = 4$ (square), and $N = 5$ (pentagon), assuming a unit circle with $r = 1$.

- **For $N = 3$ (Triangle):**
  - **Lower Bound**: $\pi_{\text{inscribed}} = 3 \cdot \sin(180/3) = 3 \cdot \frac{\sqrt{3}}{2} \approx 2.598$
  - **Upper Bound**: $\pi_{\text{circumscribed}} = 3 \cdot \tan(180/3) = 3 \cdot \sqrt{3} \approx 5.196$

- **For $N = 4$ (Square):**
  - **Lower Bound**: $\pi_{\text{inscribed}} = 4 \cdot \sin(180/4) = 4 \cdot \frac{\sqrt{2}}{2} \approx 2.828$
  - **Upper Bound**: $\pi_{\text{circumscribed}} = 4 \cdot \tan(180/4) = 4 \cdot 1 = 4.000$

- **For $N = 5$ (Pentagon):**
  - **Lower Bound**: $\pi_{\text{inscribed}} = 5 \cdot \sin(180/5) \approx 2.938$
  - **Upper Bound**: $\pi_{\text{circumscribed}} = 5 \cdot \tan(180/5) \approx 3.632$

### Table of Results:

| **N (Sides)** | **Lower Bound (Inscribed)** | **Upper Bound (Circumscribed)** |
|---------------|-----------------------------|---------------------------------|
| 3             | 2.598                       | 5.196                           |
| 4             | 2.828                       | 4.000                           |
| 5             | 2.938                       | 3.632                           |

---

### Visualizing the Approximation Process:

As we increase the number of sides $N$ in the polygon, both the inscribed and circumscribed polygons converge towards the circle's true circumference. This results in a closer approximation of π. For example, a triangle ($N=3$) provides a very rough estimate, while a pentagon ($N=5$) offers a better approximation. As $N \to \infty$, the bounds converge, and the perimeter of the polygons approaches the circumference of the circle exactly, thus giving a more precise value of π.

### Connection to Finite Element Method (FEM):

The discretization of a circle into polygons is a basic example of the FEM concept in numerical analysis. In FEM, a complex structure is divided into simpler, finite elements. Each element is analyzed individually, and the results are combined to approximate the behavior of the entire structure. Here, by increasing the number of sides $N$, the polygon "elements" become closer to the circular "whole," achieving a more accurate approximation.

---

### Summary

1. **Lower Bound**: Calculated using an inscribed polygon, gives a perimeter less than the circle’s circumference.
2. **Upper Bound**: Calculated using a circumscribed polygon, gives a perimeter greater than the circle’s circumference.
3. **Convergence**: As $N$ increases, both bounds converge to the actual circumference, yielding a more accurate value for π.

By understanding these bounds, we can appreciate how increasing the discretization level (number of sides) improves the approximation, which is a fundamental principle in FEM for analyzing complex shapes.

---
