# Parallel-Computing-for-a-Phase-Field-Model-of-Antiplane-Fracture-Using-FreeFEM


## Governing Equations

The governing equations of the antiplane phase-field fracture model are given by

\begin{cases}
\rho \dfrac{\partial^2 u}{\partial t^2}
= \operatorname{div}\left((1-z)^2\mu\nabla u\right)
& \text{in } \Omega, \\[8pt]
\alpha \dfrac{\partial z}{\partial t}
=
\left(
\epsilon\operatorname{div}(\gamma\nabla z)
-\dfrac{\gamma}{\epsilon}z
+\mu|\nabla u|^2(1-z)
\right)_+
& \text{in } \Omega.
\end{cases}
