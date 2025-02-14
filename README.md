# <p align="center"> Lagrangian Mechanics </p>

In this repo I'll add all my projects involving ***Lagrangian Mechanics*** to solve complex dynamic systems.

This formulation of classical mechanics is based on the **principle of least action** or **Hamilton's principle**, it simply states that a system chooses a path
where the **action** is minimized, this principle is formalized the following way:

  $$ \delta S=0,\quad\mathrm{where}\quad S=\int_{t_1}^{t_2}L(q,\dot{q},t)dt $$

The "recipe" to get a function $L$ that minimizes the action is the **Euler-Lagrange Equation**

$$ \frac{d}{dt}\left(\frac{\partial L}{\partial\dot{q}}\right)-\frac{\partial L}{\partial q}=0 $$

where 

*  $L = T - V$ is the functional, called **Lagrangian**
*  $q$ is the **generalized coordinate**
*  $\dot{q}$ is the **generalized velocity**
