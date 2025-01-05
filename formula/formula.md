# $\mathcal{Grad}$
$$
\nabla u=
\frac{\partial u}{\partial x}\vec{e_x}+
\frac{\partial u}{\partial y}\vec{e_y}+
\frac{\partial u}{\partial z}\vec{e_z}
$$

# $\mathcal{Div}$
$$
\nabla\cdot\vec{F}=
\frac{\partial F_x}{\partial x}+
\frac{\partial F_y}{\partial y}+
\frac{\partial F_z}{\partial z}
$$

# $\mathcal{Curl}$
$$
\nabla\times \vec{F}=
\begin{vmatrix}
    \vec{e_x}&\vec{e_y}&\vec{e_z}\\
    \frac{\partial}{\partial x}&
    \frac{\partial}{\partial y}&
    \frac{\partial}{\partial z}\\
    F_x & F_y & F_z
\end{vmatrix}\\
=(\frac{\partial F_z}{\partial y}
-\frac{\partial F_y}{\partial z})\vec{e_x}\\
+(\frac{\partial F_x}{\partial z}
-\frac{\partial F_z}{\partial x})\vec{e_y}\\
+(\frac{\partial F_y}{\partial x}
-\frac{\partial F_x}{\partial y})\vec{e_z}
$$

# $\mathcal{Div}$ $\mathcal{of}$ $\mathcal{Grad}$
$$
\nabla^2 u=
\frac{\partial^2 u}{\partial x^2}+
\frac{\partial^2 u}{\partial y^2}+
\frac{\partial^2 u}{\partial z^2}
$$

# $\mathcal{Laurent}$
$$
f(z)=\frac{1}{2\pi j}\sum_{n=-\infty}^{+\infty}
\oint_{C}\frac{f(z)}{(z-z_0)^{n+1}}dz\cdot(z-z_0)^n
$$

# $\mathcal{Taylor}$
$$
f(x)=\sum^{+\infty}_{n=0}
\frac{f^{(n)}(x_0)}{n!}(x-x_0)^n
$$

# $\mathcal{Fourier}$
$$
F(\omega)=\int^{+\infty}_{-\infty}f(t)e^{-j\omega t}dt
$$
$$
f(t)=\frac{1}{2\pi}
\int^{+\infty}_{-\infty}F(\omega)e^{j\omega t}d\omega
$$
$$
F(\Omega)=\sum^{+\infty}_{-\infty}f(n)e^{-jn\Omega}
$$
$$
f(n)=\frac{1}{2\pi}\int_{-\pi}^{+\pi}
F(\Omega)e^{(jn\Omega)}d\Omega
$$

# $\mathcal{Laplace}$
$$
F(s)=\int^{+\infty}_{0}f(t)e^{-st}dt
$$
$$
f(t)=\frac{1}{2\pi j}
\int^{\sigma+j\infty}_{\sigma-j\infty}F(s)e^{st}ds
$$

# $\mathcal{Z}$
$$
F(z)=\sum_{n=0}^{+\infty}f(n)z^{-n}
$$
$$
f(n)=\frac{1}{2\pi j}\oint_{C}F(z)z^{n-1}dz
$$

$$
\frac{\mathrm{d}}{\mathrm{d}t}
\oint\vec{B}\cdot\mathrm{d}\vec{S}
=\oint\frac{\partial\vec{B}}{\partial t}\cdot\mathrm{d}\vec{S}+
\oint\vec{B}\cdot\mathrm{d}\frac{\partial\vec{S}}{\partial t} 
$$

$$
\nabla\times\vec{H}=\frac{\partial\vec{D}}{\partial t}
\quad,\quad
\nabla\times\vec{E}=-\frac{\partial\vec{B}}{\partial t}
$$