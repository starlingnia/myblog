---
title: 你必须想象费米们是幸福的
date: 2025-10-05
categories: physics
layout: posts
mathjax: true
---
---
title: "Dirac Field Notes (Markdown / MathJax)"
date: 2025-10-10
---


srednicki notation

gamma matrix:

$$
    \gamma^\mu \equiv
    \begin{pmatrix}0 & \sigma_{a\dot{c}}^\mu\\
        \bar{\sigma}^{\mu\dot{a}c} & 0
    \end{pmatrix}
$$

the transformation:

<div type="math/tex; mode=display" text-align: center;>
$$
\left[U^{-1}(\Lambda) O_{\{\sigma\}} U(\Lambda )\right]_{\{\sigma^\prime\}}= 
\mathcal{P}(\Lambda)^{\sigma}_{\sigma^\prime} 
O_{\{\sigma\}} 
$$
</div>


what I mean here is that

a change for operator itself that change its index(collection of
coordinate and spinor index, and so on)

Specifically:

Lorentz transformation:

<div type="math/tex; mode=display" text-align: center;>
$$
U^{-1}(\Lambda) O_{\{\sigma,x\}} U(\Lambda )= 
\Lambda ^{\sigma}_{\sigma^\prime} 
O_{\{\sigma, \Lambda^{-1} x\}} 
$$
</div>

orbital anglar momentum operator:

<div type="math/tex; mode=display" text-align: center;>
$$
\mathcal{L}^{\mu\nu}\equiv
 - i\hbar(x^\mu\partial^\nu-x^\nu\partial^\mu)
$$
</div>

<div type="math/tex; mode=display" text-align: center;>
$$
e^{-i \omega_{\mu \nu } \mathcal{M}^{\mu \nu }}\phi_{\sigma}
e^{i \omega_{\mu \nu } \mathcal{M}^{\mu \nu }} = \mathcal{J}[\mathcal{M}]^a_b \phi_{\sigma}
$$
</div>

a,b means some transformation for index $\sigma$

<div type="math/tex; mode=display" text-align: center;>
$$
i [\phi,\mathcal{M}^{\mu \nu }  ]
=i\mathcal{L}^{\mu \nu }\phi+i
\mathcal{S}^{\mu \nu }\phi
$$
</div>

useful formula:

$$
\vartheta (x^0-y^0) = \int_{\mathcal C} 
\frac{d \omega }{2\pi i} \frac{e^{i \omega (x^0-y^0)}}{\omega - i \epsilon } 
$$

boson:

$$
\bra{\mathrm{ground}} \mathcal{T} \phi(x)\phi(y)
\ket{\mathrm{ground}}
$$

$$
=\vartheta (x^0-y^0)
\bra{\mathrm{ground}}\phi(x)\phi(y)
\ket{\mathrm{ground}}
+\vartheta (y^0-x^0)
\bra{\mathrm{ground}}\phi(y)\phi(x)
\ket{\mathrm{ground}}
$$

dyson equation:

$$
\bra{\mathrm{ground}} \frac{\delta S}{\delta \phi } 
\cdot \mathrm{polynomial}[\phi]
\ket{\mathrm{ground}}
=i\cdot \mathrm{contact\ term } 
$$

that's non-perturbative for Green function

For free theory or for interacting picture, we have

$$
\varphi(\mathbf{x},t)=\int\frac{d^3k}{2\omega}
\left[a(\mathbf{k})e^{i\mathbf{k}\cdot\mathbf{x}-
i\omega t}+a^\dagger(\mathbf{k})e^{i\mathbf{k}
\cdot\mathbf{x}+i\omega t}\right]
$$

in this case:

$$
\vartheta (x^0-y^0)
\bra{\mathrm{ground}}\varphi(x)\varphi(y)
\ket{\mathrm{ground}}
=
\int_\mathcal{C} 
\frac{d \ell}{2\pi i}
 \frac{e^{i \ell (x^0-y^0)}}
 {\ell - i \epsilon } 
 \int \widetilde{dp} \widetilde{d p^\prime}
 e^{ipx-ip^\prime y}\bra{\Omega}{a(\mathbf{p})a^\dagger(\mathbf{p^\prime})}\ket{\Omega }
$$

this is the free retard wightman function G$_-$.

apply the commulation relation:

$$
\bra{\Omega}{a(\mathbf{p})a^\dagger(\mathbf{p^\prime})}\ket{\Omega }
=2p^0(2\pi)^3\delta^{(3)}(p-p^\prime)
$$

$$
\mathrm{G}_R=
\int_\mathcal{C} 
\frac{d \ell}{2\pi i}
 \frac{e^{i \ell (x^0-y^0)}}
 {\ell - i \epsilon } 
 \int \widetilde{d p}\ e^{ip(x-y)}
 =
 \int_\mathcal{C} 
\frac{d \ell}{2\pi i}\widetilde{d p}
\frac{e^{i( \ell -p^0)(x^0-y^0)+i\mathbf{p}(\mathbf{x}-\mathbf{y})}}
{\ell - i \epsilon } 
$$

$$
= \int_\mathcal{C} 
\frac{d \omega dp }{(2\pi)^{4}}
\frac{e^{-i\omega(x^0-y^0)+i\mathbf{p}(\mathbf{x}-\mathbf{y})}}
{p^0 -\omega- i \epsilon }\cdot\left(-i(2p^0)^{-1}\right) 
$$

same caculation for advanced wightman function:

$$
\mathrm{G}_+=
\int_\mathcal{C} 
\frac{d \omega dp }{(2\pi)^{4}}
\frac{e^{-i\omega(y^0-x^0)+i\mathbf{p}(\mathbf{y}-\mathbf{x})}}
{p^0 -\omega- i \epsilon }\cdot\left(-i(2p^0)^{-1}\right) 
$$

we apply a transformation that: $\omega,\mathbf{p} \rightarrow -\omega, -\mathbf{p}$

$$
\mathrm{G}_A
= \int_\mathcal{C} 
\frac{d \omega dp }{(2\pi)^{4}}
\frac{e^{-i\omega(x^0-y^0)+i\mathbf{p}(\mathbf{x}-\mathbf{y})}}
{p^0 +\omega- i \epsilon }\cdot\left(-i(2p^0)^{-1}\right) 
$$

then apparently,

apply formula that : 

$$\frac{1}{p^0-\omega-i \epsilon} 
=\frac{p^0+\omega}{(p^0)^2-\omega^2-2i\omega\epsilon+ \epsilon ^2}+i 
\frac{\epsilon }{(p^0)^2-\omega^2-2i\omega\epsilon+ \epsilon ^2}
$$

we do approximation up to $\epsilon$\ :\ 

$$\frac{1}{p^0-\omega-i \epsilon} 
=\frac{p^0+\omega}{(p^0)^2-\omega^2}+2\pi i \delta(p^0-\omega)
$$

feyman Green function, or causual Green function:

<div type="math/tex; mode=display" text-align: center;>
$$
\mathcal{G}= G_A+G_R
$$
</div>

$$
=\int_\mathcal{C} 
\frac{d \omega dp }{(2\pi)^{4}}
\frac{e^{-i\omega(x^0-y^0)+i\mathbf{p}(\mathbf{x}-\mathbf{y})}}
{(p^0)^2-\omega^2}\cdot 2p^0
\cdot\left(-i(2p^0)^{-1}\right) 
$$

$$
+i\cdot\int_\mathcal{C} 
\frac{d \omega dp }{(2\pi)^{4}}
e^{-i\omega(x^0-y^0)+i\mathbf{p}(\mathbf{x}-\mathbf{y})}\cdot
\left(-i(2p^0)^{-1}\right)\cdot
 \left(2\pi\delta(p^0-\omega)+2\pi\delta(p^0+\omega)\right)
$$

one can check that, this is exactly the expression:

$$
\mathcal{G}= \int_{\mathcal{F}} \frac{d^4 p}{(2\pi)^4} \frac{-i}
{p^2+m^2}
 e^{-i\omega(x^0-y^0)+i\mathbf{p}(\mathbf{x}-\mathbf{y})}
$$

for fermion case:

$$
\bra{\mathrm{ground}} \mathcal{T} \overline{\psi(x)}\psi(y)
\ket{\mathrm{ground}}
$$

$$
=\vartheta (x^0-y^0)
\bra{\mathrm{ground}}\overline{\psi(x)}\psi(y)
\ket{\mathrm{ground}}
-\vartheta (y^0-x^0)
\bra{\mathrm{ground}}\psi(y)\overline{\psi(x)}
\ket{\mathrm{ground}}
$$

 the free theory or the interacting picture has expansion:

 $$
\psi(x)=\sum_{s=\pm}\int\widetilde{dp}
 \left[b_s(\mathbf{p})u_s(\mathbf{p})e^{ipx}
 +d_s^\dagger(\mathbf{p})v_s(\mathbf{p})e^{-ipx}\right]
$$

 for this femion Green function:

$$
\vartheta (x^0-y^0)
\bra{\mathrm{ground}}\overline{\psi(x)}\psi(y)
\ket{\mathrm{ground}}
=\int_{\mathcal C} 
\frac{d \omega }{2\pi i} \frac{e^{i \omega (x^0-y^0)}}{\omega - i \epsilon }
\times\int \widetilde{dp} \widetilde{d p^\prime}
\left(\langle
d_sd^\dagger_s
\rangle v_s \bar{v}_s e^{ipx-ip^\prime y}
\right)
$$

for srednicki, we have:

<div type="math/tex; mode=display" text-align: center;>
$$
\langle
d_sd^\dagger_s
\rangle
=\langle
\{d_s,d^\dagger_s\}
\rangle
=2p^0(2\pi)^3\delta^3(p-p^\prime)
$$
</div>

$$
 v_s \bar{v_s} = -p\!\!\!/-m
$$

thus,

$$
G_R = \int_{\mathcal C} 
\frac{d \omega }{2\pi i} \frac{e^{i(\omega-p^0) (x^0-y^0)}}{\omega - i \epsilon }
\times \int \frac{d^3 p}{(2\pi)^32p^0}(-p\!\!\!/-m)
e^{i\mathbf{p}(\mathbf{x}-\mathbf{y})}
$$

$$
=\int_{\mathcal C} 
\frac{d \ell }{2\pi i} \frac{e^{-i\ell (x^0-y^0)}}{p^0-\ell- i \epsilon }
\times \int \frac{d^3 p}{(2\pi)^32p^0}(-p\!\!\!/-m)e^{i\mathbf{p}(\mathbf{x}-\mathbf{y})}
$$

$$
G_A
=-\int_{\mathcal C} 
\frac{d \ell }{2\pi i} \frac{e^{-i\ell (y^0-x^0)}}{p^0-\ell- i \epsilon }
\times \int \frac{d^3 p}{(2\pi)^32p^0}(-p\!\!\!/+m)e^{i\mathbf{p}(\mathbf{y}-\mathbf{x})}
$$

$$
=-\int_{\mathcal C} 
\frac{d \ell }{2\pi i} \frac{e^{-i\ell (x^0-y^0)}}{p^0+\ell- i \epsilon }
\times \int \frac{d^3 p}{(2\pi)^3 2p^0}(-p\!\!\!/+m)|_{\mathbf p \rightarrow - \mathbf p}e^{i\mathbf{p}(\mathbf{x}-\mathbf{y})}
$$

$$\frac{1}{p^0-\omega-i \epsilon} 
=\frac{p^0+\omega}{(p^0)^2-\omega^2-2i\omega\epsilon+ \epsilon ^2}+i 
\frac{\epsilon }{(p^0)^2-\omega^2-2i\omega\epsilon+ \epsilon ^2}
$$

<div type="math/tex; mode=display" text-align: center;>
$$
\mathcal{G}=G_A+G_R
$$
</div>

$$
=\int_{\mathcal C} 
\frac{d \ell }{2\pi }\frac{d^3 p}{(2\pi)^32p^0}
\frac{-ie^{ip(x-y)}}{(p^0)^2-\ell^2}\left(
(p^0+\ell)(-p\!\!\!/-m)-(p^0-\ell)(-p\!\!\!/+m)|_{\mathbf p \rightarrow - \mathbf p}\right)
$$

$$
=\int_{\mathcal C} 
\frac{d \ell }{2\pi }\frac{d^3 p}{(2\pi)^32p^0}
\frac{-ie^{ip(x-y)}}{(p^0)^2-\ell^2}\left(
(p^0+\ell)\left(
    \begin{array}{cc}
        -m&p^0-p\cdot \sigma \\
   p^0+ p\cdot \sigma&-m
    \end{array}
\right)-(p^0-\ell)\left(
    \begin{array}{cc}
        m&p^0+p\cdot \sigma \\
   p^0- p\cdot \sigma&m
    \end{array}
\right)\right)
$$

$$
=\int_{\mathcal C} 
\frac{d \ell }{2\pi }\frac{d^3 p}{(2\pi)^32p^0}
\frac{-ie^{ip(x-y)}}{(p^0)^2-\ell^2}(\left(
    \begin{array}{cc}
       -2mp^0 & 2\ell p^0-2p^0 p\cdot \sigma \\
   2\ell p^0+ 2p^0 p\cdot \sigma&-2mp^0
    \end{array}
\right))
$$

$$
=\int\frac{d^4 p}{(2\pi)^4} \frac{-ie^{ip(x-y)}}{p\!\!\!/-m} 
$$

the same caculation applied for 

<div type="math/tex; mode=display" text-align: center;>
$$\bra{\mathrm{ground}} \mathcal{T} \psi(x)\overline{\psi(y)}
\ket{\mathrm{ground}}$$
</div>

just assign an negative sign before mass, we got result:

<div type="math/tex; mode=display" text-align: center;>
$$
\mathcal{G}=
\int\frac{d^4 p}{(2\pi)^4} \frac{-ie^{ip(x-y)}}{p\!\!\!/+m} 
$$
</div>
