---
layout: slide
theme: white
transition: slide
---

<section data-markdown>

The electric fields of two EM waves in vacuum are both described by:

$$\mathbf{E} = E_0 \sin(kx-\omega t)\hat{y}$$

The "wave number" $k$ of wave 1 is larger than that of wave 2, $k_1 > k_2$. Which wave has the larger frequency $f$?

1. Wave 1
2. Wave 2
3. impossible to tell

Note:
* Correct Answer: A
* Same speed and thus wavelength of 1 is smaller, so frequency is higher

</section>

<section data-markdown>
## Announcements

* Projects graded! Sync to see your detailed grades.
* Projected grades sent out
* Homework 9 will be posted by tomorrow morning (Apologies, I'm jet lagged)

</section>

<section data-markdown>
For a wave on a 1d string that hits a boundary between 2 strings of different material we get,

$$\widetilde{f}(z<0) = \widetilde{A}_I e^{i(k_1)z-\omega t} + \widetilde{A}_Re^{i(-k_1z-\omega t)}$$
$$\widetilde{f}(z>0) = \widetilde{A}_T e^{i(k_2)z-\omega t}$$

where continuity (BCs) give,

$$\widetilde{A}_R = \left(\dfrac{k_1-k_2}{k_1+k_2}\right)\widetilde{A}_I$$
$$\widetilde{A}_T = \left(\dfrac{2k_1}{k_1+k_2}\right)\widetilde{A}_I$$

Is the transmitted wave in phase with the incident wave?

A) Yes, always B) No, never C) Depends

Note:
* Correct answer: A

</section>

<section data-markdown>
For a wave on a 1d string that hits a boundary between 2 strings of different material we get,

$$\widetilde{f}(z<0) = \widetilde{A}_I e^{i(k_1)z-\omega t} + \widetilde{A}_Re^{i(-k_1z-\omega t)}$$
$$\widetilde{f}(z>0) = \widetilde{A}_T e^{i(k_2)z-\omega t}$$

where continuity (BCs) give,

$$\widetilde{A}_R = \left(\dfrac{k_1-k_2}{k_1+k_2}\right)\widetilde{A}_I$$
$$\widetilde{A}_T = \left(\dfrac{2k_1}{k_1+k_2}\right)\widetilde{A}_I$$

Is the reflected wave in phase with the incident wave?

A) Yes, always B) No, never C) Depends

Note:
* Correct answer: C
* Can be 180 out of phase

</section>

<section data-markdown>

In matter we have,

$$\nabla \cdot \mathbf{D} = \rho_f \qquad \nabla \cdot \mathbf{B} = 0$$
$$\nabla \times \mathbf{E} = -\dfrac{\partial \mathbf{B}}{\partial t} \qquad \nabla \times \mathbf{H} = \mathbf{J}_f + \dfrac{\partial \mathbf{D}}{\partial t}$$
with
$$\mathbf{D} = \varepsilon_0 \mathbf{E} + \mathbf{P} \qquad \mathbf{H} = \mathbf{B}/\mu_0 - \mathbf{M}$$

If there are no free charges or current, is $\nabla \cdot \mathbf{E} = 0$?

1. Yes, always
2. Yes, under certain conditions (what are they?)
3. No, in general this will not be true
4. ??

Note:
* Correct answer: B
</section>

<section data-markdown>

In linear dielectrics, $\mathbf{D} = \varepsilon_0\mathbf{E} + \mathbf{P} = \varepsilon \mathbf{E}.$ In a linear dielectric is $\varepsilon > \varepsilon_0$?

1. Yes, always
2. No, never
3. Sometimes, it depends on the details of the dielectric.

Note:
* Correct answer: A

</section>

<section data-markdown>

In a non-magnetic, linear dielectric,

$$v = \dfrac{1}{\sqrt{\mu \varepsilon}} = \dfrac{1}{\sqrt{\mu \varepsilon_r \varepsilon_0}} = \dfrac{c}{\sqrt{\varepsilon_r}}$$

How does $v$ compare to $c$?

1. $v>c$ always
2. $v<c$ always
3. It depends

Note:
* Correct Answer: B

</section>
