# Influence Functions, the Kaczmarz Way

An interactive tutorial on influence functions for 2-D least squares, seen through the
Kaczmarz method of projections. Observations are lines, residuals are signed distances,
and a new line with adjustable strength ε moves the least-squares solution by the
Sherman–Morrison rank-1 update. The page shows the exact change of every residual,
the first-order (influence-function) prediction, and a Kaczmarz/SGD animation.

Live page: https://yaroslavvb.github.io/influence-functions-tutorial/

Single self-contained `index.html` (canvas + KaTeX from cdnjs).

Second page, `price-of-influence.html`: the general derivation (why the inverse Hessian), how it is made computable (Gauss-Newton, damping, EK-FAC, ASTRA), and a live cost calculator for every step at Llama-3-8B scale.

Live: https://yaroslavvb.github.io/influence-functions-tutorial/price-of-influence.html
