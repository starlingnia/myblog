---
title: 你必须想象费米们是幸福的
date: 2025-10-05
categories: physics
layout: page
mathjax: true
---
---
title: "Dirac Field Notes (Markdown / MathJax)"
date: 2025-10-10
---


for Dirac basis (with + - - -):

$$
p\!\!\!/-m =
\begin{pmatrix}
p^0-m & -\vec{p}\cdot\vec{\sigma}\\[6pt]
\vec{p}\cdot\vec{\sigma} & -p^0-m
\end{pmatrix}
$$

mode:

$$
u(\vec p )=
\begin{pmatrix}
(p^0+m)\phi\\[6pt]
(\vec p\cdot\vec \sigma)\phi
\end{pmatrix}
$$

for $p\!\!\!/ +m$:

$$
\begin{pmatrix}
p^0+m & -\vec p\cdot\vec \sigma\\[6pt]
\vec p\cdot\vec \sigma & - p^0+m
\end{pmatrix}
$$

it could be written as:

$$
(p\!\!\!/ +m)
\begin{pmatrix}
\phi\\[6pt]
0
\end{pmatrix}
$$

so, after appreciated normalization:

$$
u^{(\pm)}=\mathcal{N} (p\!\!\!/ +m)
\begin{pmatrix}
\phi^{(\pm)}\\[6pt]
0
\end{pmatrix}
$$

we conclude:

$$
u=(\sqrt{p^0+m})^{-1}(p\!\!\!/ +m)
\begin{pmatrix}
\phi^{\pm}\\[6pt]
0
\end{pmatrix}
\tag{15}
$$

Then,

$$
u^\dagger =(\sqrt{p^0+m})^{-1} \big(\phi^\pm ,\ 0\big)
\begin{pmatrix}
p^0+m & \vec p\cdot\vec \sigma\\[6pt]
-\vec p\cdot\vec \sigma & - p^0+m
\end{pmatrix}
$$

Thus,

$$
\sum_{\pm} uu^\dagger = (p^0+m)^{-1}
\begin{pmatrix}
p^0+m&-\vec p\cdot\vec \sigma\\[6pt]
\vec p\cdot\vec \sigma& - p^0+m
\end{pmatrix}
\sum_{\pm}
\begin{pmatrix}
\phi^{\pm}\\[6pt]
0
\end{pmatrix}
(\phi^\pm ,\ 0)
\begin{pmatrix}
p^0+m&\vec p\cdot\vec \sigma\\[6pt]
-\vec p\cdot\vec \sigma& - p^0+m
\end{pmatrix}
$$

$$
=
(p^0+m)^{-1}
\begin{pmatrix}
p^0+m&-\vec p\cdot\vec \sigma\\[6pt]
\vec p\cdot\vec \sigma& - p^0+m
\end{pmatrix}
\begin{pmatrix}
1_{2\times2}&0\\[6pt]
0&0
\end{pmatrix}
\begin{pmatrix}
p^0+m&\vec p\cdot\vec \sigma\\[6pt]
-\vec p\cdot\vec \sigma& - p^0+m
\end{pmatrix}
$$

$$
=
(p^0+m)^{-1}
\begin{pmatrix}
p^0+m&-\vec p\cdot\vec \sigma\\[6pt]
\vec p\cdot\vec \sigma& - p^0+m
\end{pmatrix}
\begin{pmatrix}
p^0+m&\vec p\cdot\vec \sigma\\[6pt]
0&0
\end{pmatrix}
$$

$$
=
(p^0+m)^{-1}
\begin{pmatrix}
(p^0+m)^2 & (p^0+m)\,\vec p\cdot\vec \sigma\\[6pt]
(p^0+m)\,\vec p\cdot\vec \sigma & (\vec p\cdot\vec \sigma)^2
\end{pmatrix}
$$

Notice that $(\vec p\cdot\vec  \sigma)^2 = \vec p^{\,2} = (p^0)^2-m^2=(p^0+m)(p^0-m)$.

$$
\sum_{\pm} uu^\dagger
=
\begin{pmatrix}
p^0+m & \vec p\cdot\vec \sigma\\[6pt]
\vec p\cdot\vec \sigma & p^0-m
\end{pmatrix}
=
(p\!\!\!/ +m)\gamma^0
\tag{16}
$$

Where

$$
\gamma^0=
\begin{pmatrix}
1_{2\times2}&0\\[6pt]
0&-1_{2\times2}
\end{pmatrix}
$$

By the definition: $\bar u = u^\dagger \gamma^0$.

We simply get:

$$
\sum_{\pm} u\bar u =(p\!\!\!/ +m)\gamma^0\gamma^0=p\!\!\!/ +m
\tag{17}
$$



For negative frequency $k=-p$ case:

$$
p\!\!\!/ _\mu+m = -k\!\!\!/ _\mu+m=
\begin{pmatrix}
-k^0+m & \vec k\cdot\vec \sigma\\[6pt]
-\vec k\cdot\vec \sigma & k^0+m
\end{pmatrix}
$$

We pick up the solution

$$
\begin{pmatrix}
(\vec k\cdot\vec \sigma )\chi^{\pm}\\[6pt]
(k^0+m)\chi^{\pm}
\end{pmatrix}
$$

Where

$$
\chi^{+}=\begin{pmatrix}1\\[2pt]0\end{pmatrix},\qquad
\chi^{-}=\begin{pmatrix}0\\[2pt]1\end{pmatrix}.
$$

$$
v=(\sqrt{-p^0+m})^{-1}(-p\!\!\!/ +m)
\begin{pmatrix}
0\\[6pt]
\chi^{\pm}
\end{pmatrix}
\tag{23}
$$

The dagger of $v$ will become:

$$
v^\dagger =(\sqrt{p^0+m})^{-1} \big(0,\ \chi^\pm \big)
\begin{pmatrix}
-p^0+m & -\vec p\cdot\vec \sigma\\[6pt]
\vec p\cdot\vec \sigma & p^0+m
\end{pmatrix}
$$

Thus,

$$
\sum_{\pm} vv^\dagger = (p^0+m)^{-1}
\begin{pmatrix}
-p^0+m & \vec p\cdot\vec \sigma\\[6pt]
-\vec p\cdot\vec \sigma & p^0+m
\end{pmatrix}
\sum_{\pm}
\begin{pmatrix}
0\\[6pt]
\chi^{\pm}
\end{pmatrix}
(0,\ \chi^\pm)
\begin{pmatrix}
-p^0+m & -\vec p\cdot\vec \sigma\\[6pt]
\vec p\cdot\vec \sigma & p^0+m
\end{pmatrix}
$$

$$
=
(p^0+m)^{-1}
\begin{pmatrix}
-p^0+m & \vec p\cdot\vec \sigma\\[6pt]
-\vec p\cdot\vec \sigma & p^0+m
\end{pmatrix}
\begin{pmatrix}
0 & 0\\[6pt]
0 & 1_{2\times2}
\end{pmatrix}
\begin{pmatrix}
-p^0+m & -\vec p\cdot\vec \sigma\\[6pt]
\vec p\cdot\vec \sigma & p^0+m
\end{pmatrix}
$$

$$
=
(p^0+m)^{-1}
\begin{pmatrix}
-p^0+m & \vec p\cdot\vec \sigma\\[6pt]
-\vec p\cdot\vec \sigma & p^0+m
\end{pmatrix}
\begin{pmatrix}
0 & 0\\[6pt]
\vec p\cdot\vec \sigma & p^0+m
\end{pmatrix}
$$

$$
=
(p^0+m)^{-1}
\begin{pmatrix}
(\vec p\cdot\vec \sigma)^2 & (p^0+m)(\vec p\cdot\vec \sigma)\\[6pt]
(p^0+m)(\vec p\cdot\vec \sigma) & (p^0+m)^2
\end{pmatrix}
$$

Notice that $(\vec p\cdot\vec  \sigma)^2 = \vec p^{\,2} = (p^0)^2-m^2=(p^0+m)(p^0-m)$.

$$
\sum_{\pm} vv^\dagger =
\begin{pmatrix}
p^0-m & \vec p\cdot\vec \sigma\\[6pt]
\vec p\cdot\vec \sigma & p^0+m
\end{pmatrix}
= -(-p\!\!\!/ +m)\gamma^0
\tag{24}
$$

Where $\gamma^0$ as before.

By the definition: $$\bar v = v^\dagger \gamma^0$$.


We simply get:

$$
\sum_{\pm} v\bar v = -(- p\!\!\!/ +m)\gamma^0\gamma^0= p\!\!\!/ -m
\tag{25}
$$





Field expansion:

$$
\psi(x) = \int \widetilde{dp}\ \sum _ { \pm } \Big[ b _ { \pm } ( p ) u ^ { ( \pm ) } ( p ) e ^ { - i p x } + d ^ { ( \pm )\dagger } ( p )v^{(\pm)}(p) e ^ { i p x }  \Big]
$$

Anticommutator:

$$
\{ \psi , \psi^{\dagger} \} =
\int  \widetilde {dp}\ \widetilde {d q }\Big\{
 \sum_ {\pm} b_{ \pm } u^{ (\pm)} e ^ { -ip^0t+ i\vec p\cdot\vec x }
 + d _ { \pm } ^ { \dagger }v^{(\pm)}e ^ { ip^0t-i\vec p\cdot\vec x },\ 
 \sum _ { \pm } b _ { \pm } ^ { \dagger } u ^ { (\pm)\dagger } e ^ { iq^0t- i\vec q\cdot\vec x' } + d _ { \pm } v^{(\pm)\dagger} e ^ { -iq^0t+i \vec q\cdot\vec x' } \Big\}
$$

This reduces to

$$
=\int 
\widetilde{dp}\ \widetilde{dq}\ 
\big(2q^{0}(2\pi)^{3}\delta^{(3)}(p-q)\big)
\sum_{\pm}\big(u_{\pm}u_{\pm}^{\dagger}e^{i\vec p\cdot(\vec x-\vec x')}+v_{\pm}v_{\pm}^{\dagger}e^{-i\vec p\cdot(\vec x-\vec x')}\big)
$$

$$
=\int\widetilde{dp}\ \big[(p\!\!\!/+m)\gamma^{0}e^{i\vec p\cdot(\vec x-\vec x')}-(-p\!\!\!/+m)\gamma^{0}e^{-i\vec p\cdot(\vec x-\vec x')}\big]
$$

Then, we take the spatial momentum in second term to opposite direction:

$$
=\int\widetilde{dp}\ \big[(p\!\!\!/+m)\gamma^{0}-(-p\!\!\!/+m)\big|_{\vec{p}\rightarrow-\vec{p}}\gamma^{0}\big] e^{i\vec p\cdot(\vec x-\vec x')}
$$

Compute the sum of matrices:

$$
\begin{pmatrix}
p^0+m & \vec{p}\cdot\vec{\sigma}\\[6pt]
\vec{p}\cdot\vec{\sigma} & p^0-m
\end{pmatrix}
+
\begin{pmatrix}
p^0-m & -\vec{p}\cdot\vec{\sigma}\\[6pt]
-\vec{p}\cdot\vec{\sigma} & p^0+m
\end{pmatrix}
= 2p^0\ \mathbf{1}_{4\times 4}
$$

We conclude,

$$
\{ \psi , \psi^{\dagger} \}=
\left( \int\frac{d^3p}{(2\pi)^{3}} e^{i\vec p\cdot(\vec x-\vec x')} \right) \mathbf{1}_{4\times4}
$$

Thus the equal-time anticommutator component:

<div type="math/tex; mode=display" text-align: center;>
$$
\{ \psi_\alpha(x) , \psi^{\dagger}_{\alpha'}(x') \}=
\delta^{(3)}(x-x')\delta_{\alpha\alpha'}
\tag{30}
$$
</div>


Hamiltonian:

<div type="math/tex; mode=display" text-align: center;>
$$
H = \int d^3x\ \bar\psi(- i\gamma^j \partial_j + m)\psi
$$
</div>


Expanding gives (intermediate steps):

$$
H = \int d^3x\ \widetilde{dp}\ \widetilde{dq}
\sum_{\sigma,\sigma'} \Big( (b_\sigma^\dagger u_\sigma^\dagger e^{-i\vec q\cdot\vec x} + d_\sigma v_\sigma^\dagger e^{i\vec q\cdot\vec x})\gamma^0\big((\gamma^j p^j + m) b_{\sigma'} u_{\sigma'} e^{i\vec p\cdot\vec x} + (-\gamma^j p^j + m) d_{\sigma'}^\dagger v_{\sigma'} e^{-i\vec p\cdot\vec x}\big)\Big)
$$

Notice that:

$$
\sum_{\sigma,\sigma'} u_{\sigma}^\dagger\gamma^0(\gamma^j p^j + m)u_{\sigma'}
= \sum_{\sigma,\sigma'}
\frac{\big((p^0+ m )\phi^\sigma,\ -\vec{p}\cdot\vec{\sigma}\phi^\sigma\big)}
{(p^0+m)}
\begin{pmatrix}
m & \vec{p}\cdot\vec{\sigma}\\[6pt]
-\vec{p}\cdot\vec{\sigma} & m
\end{pmatrix}
\begin{pmatrix}
(p^0+m)\phi^{\sigma'}\\[6pt]
\vec{p}\cdot\vec{\sigma}\phi^{\sigma'}
\end{pmatrix}
$$

Working out the product:

$$
= \sum_{\sigma,\sigma'} \frac{\big((p^0+ m )\phi^\sigma,\ -\vec{p}\cdot\vec{\sigma}\phi^\sigma\big)}
{(p^0+m)}
\begin{pmatrix}
m( p^0+m)\phi^{\sigma'}+((p^0)^2-m^2)\phi^{\sigma'}\\[6pt]
-p^0\ \vec{p}\cdot\vec{\sigma}\phi^{\sigma'}
\end{pmatrix}
$$

Using orthonormality of $\phi^\sigma$'s, this becomes:

<div type="math/tex; mode=display" text-align: center;>
$$
= \sum_{\sigma,\sigma'} \delta_{\sigma,\sigma'}\big(m(p^0+m)+((p^0)^2-m^2)+p^0(p^0-m)\big)
= \sum_{\sigma,\sigma'} \delta_{\sigma,\sigma'} 2(p^0)^2
$$
</div>

Similarly, u modes orthonormal to v modes, and

<div type="math/tex; mode=display" text-align: center;>
$$
\sum_{\sigma,\sigma'} v_{\sigma}^\dagger\gamma^0(-\gamma^j p^j + m)v_{\sigma'}
= \sum_{\sigma,\sigma'} \delta_{\sigma,\sigma'}(-2(p^0)^2)
$$
</div>

So, after integration of $x$ and $q$ we get only $p=q$ terms, and conclude:

$$
H = \int \widetilde{dp}\ p^0 \sum_\sigma \big(b^\dagger_\sigma b_\sigma - d_\sigma d^\dagger_\sigma \big)
$$

Reordering anticommutators:

$$
H = \int \widetilde{dp}\ p^0 \sum_\sigma \big(b^\dagger_\sigma b_\sigma + d^\dagger_\sigma d_\sigma - 2p^0(2\pi)^3\delta(0)\big)
\tag{32}
$$



Fermion Green function (time-ordered):

$$
\langle \mathrm{ground}\vert \mathcal{T}\psi(x) \overline{\psi(y)}\vert \mathrm{ground}\rangle
= \Theta (x^0-y^0)
\langle \mathrm{ground}\vert\psi(x)\overline{\psi(y)}\vert \mathrm{ground}\rangle
- \Theta (y^0-x^0)
\langle \mathrm{ground}\vert\overline{\psi(y)}\psi(x)\vert \mathrm{ground}\rangle
$$

With mode expansion:

$$
\psi(x)=\sum_{s=\pm}\int\widetilde{dp}\ \big[b_s(\mathbf{p})u_s(\mathbf{p})e^{-ipx} + d_s^\dagger(\mathbf{p})v_s(\mathbf{p})e^{ipx}\big]
$$

For the second term (with $\Theta(y^0-x^0)$), evaluate:

$$
\Theta(y^0-x^0)
\langle \mathrm{ground}\vert\overline{\psi(y)}\psi(x)\vert \mathrm{ground}\rangle
= \int_{\mathcal C} \frac{d\omega}{2\pi i} \frac{e^{i\omega (y^0-x^0)}}{\omega - i \epsilon}
\times \int \widetilde{dp}\, \widetilde{dp'}\ \langle d_sd^\dagger_s\rangle\ v_s\bar v_s\ e^{-ip y + i p' x}
$$

Using $\langle d_s d_s^\dagger\rangle = \{d_s,d_s^\dagger\} = 2p^0(2\pi)^3\delta^3(p-p')$ and $v_s\bar v_s = p\!\!\!/-m$, we get:

$$
G_A = -\int_{\mathcal C} \frac{d\omega}{2\pi i} \frac{e^{i(\omega-p^0)(y^0-x^0)}}{\omega - i\epsilon}
\times \int \frac{d^3p}{(2\pi)^3 2p^0} (p\!\!\!/-m) e^{i\mathbf{p}\cdot(\mathbf{y}-\mathbf{x})}
$$

Set $\ell=\omega-p^0$ (change variable), so

$$
G_A = -\int_{\mathcal C} \frac{d\ell}{2\pi i} \frac{e^{-i\ell (y^0-x^0)}}{p^0-\ell - i\epsilon}
\times \int \frac{d^3p}{(2\pi)^3 2p^0} (p\!\!\!/-m) e^{i\mathbf{p}\cdot(\mathbf{y}-\mathbf{x})}
$$

Similarly,

$$
G_R = \int_{\mathcal C} \frac{d\ell}{2\pi i} \frac{e^{-i\ell (x^0-y^0)}}{p^0-\ell - i\epsilon}
\times \int \frac{d^3p}{(2\pi)^3 2p^0} (p\!\!\!/+m) e^{i\mathbf{p}\cdot(\mathbf{x}-\mathbf{y})}
$$

Define $\mathcal{G}=G_A+G_R$ (full propagator)


We can rewrite $G_A$ also as:

$$
G_A = -\int_{\mathcal C} \frac{d\ell}{2\pi i} \frac{e^{-i\ell (x^0-y^0)}}{p^0+\ell - i\epsilon}
\times \int \frac{d^3p}{(2\pi)^3 2p^0} (p\!\!\!/-m)\big|_{\vec p\rightarrow -\vec p}\ e^{i\mathbf{p}\cdot(\mathbf{x}-\mathbf{y})}
$$

Using the identity (pole decomposition)

$$
\frac{1}{p^0-\omega - i\epsilon}
= \mathcal{P}\frac{p^0+\omega}{(p^0)^2-\omega^2} + \pi i\delta(p^0-\omega - i\epsilon)
$$

we separate principal value and delta contributions, which identifies poles and leads to contour choices. After some algebra (grouping terms), we obtain:

$$
\mathcal{G}=G_A+G_R
$$

$$
=
\mathcal{P}\int_{\mathcal C}
\frac{d\ell}{2\pi i}\frac{d^3p}{(2\pi)^3 2p^0}
\frac{e^{-i\ell (x^0-y^0)}e^{i\mathbf{p}\cdot(\mathbf{x}-\mathbf{y})}}{(p^0)^2-\ell^2}
\Big(
(p^0+\ell)
\begin{pmatrix}
p^0+m & -\vec p\cdot\vec\sigma\\[6pt]
\vec p\cdot\vec\sigma & -p^0+m
\end{pmatrix}
-
(p^0-\ell)
\begin{pmatrix}
p^0-m & \vec p\cdot\vec\sigma\\[6pt]
-\vec p\cdot\vec\sigma & -p^0-m
\end{pmatrix}
\Big)
$$

$$
+
\int_{\mathcal C}
\frac{d\ell}{2\pi i}\frac{d^3p}{(2\pi)^3 2p^0}
e^{-i\ell (x^0-y^0)}e^{i\mathbf{p}\cdot(\mathbf{x}-\mathbf{y})}
\big( \pi i\delta(\ell-p^0+i\epsilon)(p\!\!\!/-m) + \pi i\delta(\ell+p^0-i\epsilon)(p\!\!\!/+m)\big)
$$

After simplifying the principal-value integrand:

$$
=
\mathcal{P}\int_{\mathcal C}
\frac{d\ell}{2\pi i}\frac{d^3p}{(2\pi)^3 2p^0}
\frac{e^{-i\ell (x^0-y^0)}e^{i\mathbf{p}\cdot(\mathbf{x}-\mathbf{y})}}{(p^0)^2-\ell^2}
\Big(
2p^0
\begin{pmatrix}
0 & -\vec p\cdot\sigma\\[6pt]
\vec p\cdot\sigma & 0
\end{pmatrix}
+
\begin{pmatrix}
2p^0 m + 2p^0 \ell & 0\\[6pt]
0 & -2p^0 \ell + 2p^0 m
\end{pmatrix}
\Big)
$$

$$
+
\int_{\mathcal C}
\frac{d\ell}{2\pi i}\frac{d^3p}{(2\pi)^3 2p^0}
e^{-i\ell (x^0-y^0)}e^{i\mathbf{p}\cdot(\mathbf{x}-\mathbf{y})}
\big( \pi i\delta(\ell-p^0+i\epsilon)(p\!\!\!/-m) + \pi i\delta(\ell+p^0-i\epsilon)(p\!\!\!/+m)\big)
$$

Rewrite principal part more compactly (change measure to full 4d):

$$
=
\mathcal{P}\int_{\mathcal C}
\frac{d\ell}{2\pi}\frac{d^3p}{(2\pi)^3}
\frac{i e^{-i\ell (x^0-y^0)} e^{i\mathbf{p}\cdot(\mathbf{x}-\mathbf{y})}}
{\ell^2 - \vec p^{\,2} - m^2}
\begin{pmatrix}
\ell + m & -\vec p\cdot\sigma\\[6pt]
\vec p\cdot\sigma & -\ell + m
\end{pmatrix}
$$

$$
+
\int_{\mathcal C}
\frac{d\ell}{2\pi i}\frac{d^3p}{(2\pi)^3 2p^0}
e^{-i\ell (x^0-y^0)}e^{i\mathbf{p}\cdot(\mathbf{x}-\mathbf{y})}
\big( \pi i\delta(\ell-p^0+i\epsilon)(p\!\!\!/-m) + \pi i\delta(\ell+p^0-i\epsilon)(p\!\!\!/+m)\big)
$$

Finally, combining and restoring full 4-momentum measure:

$$
\mathcal{G}(x-y) = \int \frac{d^4 p}{(2\pi)^4}\ \frac{i\, e^{-ip\cdot(x-y)}}{p\!\!\!/-m+i\epsilon}
\tag{39}
$$

---

(End of notes)
