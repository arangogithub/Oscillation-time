# Oscillation-time
Jupyter notebooks on numerical experimentation of the oscillation time in a nonlinear pendulum 
We consider a nonlinear pendulum modeled by 
$$
\frac{d^2x}{dt^2} + 2\,\alpha  \frac{dx}{dt} + \beta\, \frac{dx}{dt}\, \left| \frac{dx}{dt} \right|  + x\, \left(1+\gamma\,f(x)\right)=0, 
\qquad x(0) = x_0, \dot{x}(0) = 0.
$$
Denote by  $\tau(x_0, \alpha, \beta)$ the time taking by the pendulum to complete one oscillation starting at $x_0$ with vanishing velocity. Fixed $x_0$, this notebook explores the dependence of $\tau$ on the damping coefficients $\alpha$ and $\beta$. The effect of an additional parameter  $\gamma$ is also considered 
