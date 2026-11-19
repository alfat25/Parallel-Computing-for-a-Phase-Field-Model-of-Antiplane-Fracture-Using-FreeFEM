# Parallel-Computing-for-a-Phase-Field-Model-of-Antiplane-Fracture-Using-FreeFEM


## Governing Equations

The governing equations of the antiplane phase-field fracture model are given by

$$
\begin{aligned}
\rho \frac{\partial^2 u}{\partial t^2}
&= \operatorname{div}\left((1-z)^2\mu\nabla u\right),
&& \text{in } \Omega, \\[6pt]
\alpha \frac{\partial z}{\partial t}
&= \left(
\epsilon\operatorname{div}(\gamma\nabla z)
-\frac{\gamma}{\epsilon}z
+\mu|\nabla u|^2(1-z)
\right)_+,
&& \text{in } \Omega.
\end{aligned}
$$

