---
layout: slide
theme: white
transition: slide
---

<section data-markdown>

Last class, we found that the wave packet that we constructed from a Gaussian distribution of $k$'s centered around $k_0$ was,

$$f(x) = e^{-x^2/4\sigma} e^{-ik_0x}$$

Sketch this wave packet.

</section>

<section data-markdown>

## Announcements
* Quiz 6 (next Friday) - Waves in conductors; details on Friday
* Volunteer for Physics and Astronomy Day (April 15, 2017)
  * [Link to Sign-up!](https://msu.co1.qualtrics.com/jfe/form/SV_1HrDNGo5gNgMsG9)

</section>

<section data-markdown>

What do y'all want to learn about after this week?
1. Potential theory and gauge (Ch. 10)
2. Accelerated charges and radiation (Ch. 11)
3. Special relativity (Ch. 12)

</section>

<section data-markdown>

Fourier tells us that we can write a "pulse" by summing up sinusoidal functions:

$f(x) = \int_{-\infty}^{\infty} a(k)e^{ikx}dk$

If we were to compute $f(x) = \int_{-\infty}^{\infty} a(k)e^{ik(x-vt)}dk$ where $v$ is a known constant, what would we get?

1. $f(x)$
2. $f(vt)$
3. $f(x-vt)$
4. Something complicated!
5. ???

Note:
* Correct Answer: C

</section>

<section data-markdown>

Fourier tells us that we can write a "pulse" by summing up sinusoidal functions:

$f(x) = \int_{-\infty}^{\infty} a(k)e^{ikx}dk$

If we were to compute $f(x) = \int_{-\infty}^{\infty} a(k)e^{ik(x-v(k)t)}dk$ where $v(k)$ is function, what would we get?

1. $f(x)$
2. $f(vt)$
3. $f(x-vt)$
4. Something more complicated!
5. ???

Note:
* Correct Answer: D

</section>

<section data-markdown>

For our atomic model of permittivity we found $\widetilde{\varepsilon}$ to be

$$\widetilde{\varepsilon} = \varepsilon_0\left(1+\dfrac{Nq^2}{\varepsilon_0 m}\sum_i \dfrac{f_i}{(\omega_i^2-\omega^2)-i\gamma_i\omega}\right)$$

We also know that $\dfrac{n}{c} = \dfrac{\widetilde{k}}{\omega} = \sqrt{\widetilde{\varepsilon}\mu}.$
* Find (and simplify) a formula for $n$, assuming the term adding to "1" above is small.
* In that limit, find $k_R$ and $k_I$. What does each one tell you, physically?
* Sketch both of these as functions of $\omega$ (assuming that only one term in that sum "dominates")

</section>
