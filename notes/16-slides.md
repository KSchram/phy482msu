---
layout: slide
theme: white
transition: slide
---

<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>

Let's return to the complete definition of Ampere's Law: $\nabla \times \mathbf{B} = \mu_0\mathbf{J} + \varepsilon_0 \mu_0 \frac{d\mathbf{E}}{dt}$.

**At location 1**, what are the signs of $J_x$, $dE_x/dt$, and $(\nabla \times \mathbf{B})_x$?

1. $J_x<0$, $dE_x/dt<0$, $(\nabla \times \mathbf{B})_x<0$
2. $J_x=0$, $dE_x/dt>0$, $(\nabla \times \mathbf{B})_x>0$
3. $J_x>0$, $dE_x/dt=0$, $(\nabla \times \mathbf{B})_x>0$
4. $J_x>0$, $dE_x/dt>0$, $(\nabla \times \mathbf{B})_x>0$
5. Something else


Note:
* Correct Answer: C
* There's no E there, Jx points to the right
</section>

<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>

Let's return to the complete definition of Ampere's Law: $\nabla \times \mathbf{B} = \mu_0\mathbf{J} + \varepsilon_0 \mu_0 \frac{d\mathbf{E}}{dt}$.

**At location 3**, what are the signs of $J_x$, $dE_x/dt$, and $(\nabla \times \mathbf{B})_x$?

1. $J_x<0$, $dE_x/dt<0$, $(\nabla \times \mathbf{B})_x<0$
2. $J_x=0$, $dE_x/dt>0$, $(\nabla \times \mathbf{B})_x>0$
3. $J_x>0$, $dE_x/dt=0$, $(\nabla \times \mathbf{B})_x>0$
4. $J_x>0$, $dE_x/dt>0$, $(\nabla \times \mathbf{B})_x>0$
5. Something else


Note:
* Correct Answer: B
* There's no Jx there, Ex points to the right
</section>

<section data-markdown>

<img src="./images/capacitor_with_x.png" align="left" style="width: 400px";/>

A pair of capacitor plates are charging up due to a current $I$. The plates have an area $A=\pi R^2$. Use the Maxwell-Ampere Law to find the magnetic field at the point "x" in the diagram as distance $r$ from the wire.

1. $B = \frac{\mu_0 I}{4 \pi r}$
2. $B = \frac{\mu_0 I}{2 \pi r}$
3. $B = \frac{\mu_0 I}{4 \pi r^2}$
4. $B = \frac{\mu_0 I}{2 \pi r^2}$
5. Something much more complicated

Note:
* Correct Answer: B

</section>

<section data-markdown>

<img src="./images/capacitor_with_x.png" align="left" style="width: 400px";/>

The plates have an area $A=\pi R^2$. Use the Gauss' Law to find the electric field between the plates, answer in terms of $\sigma$ the charge density on the plates.

1. $E = \sigma/\varepsilon_0$
2. $E = -\sigma/\varepsilon_0$
3. $E = \sigma/(\varepsilon_0 \pi R^2)$
4. $E = \sigma \pi R^2 / \varepsilon_0$
5. Something much more complicated

Note:
* Correct Answer: B

</section>

<section data-markdown>

<img src="./images/capacitor_with_x.png" align="left" style="width: 400px";/>

The plates have an area $A=\pi R^2$. Determine the relationship between the current flowing in the wires and the rate of change of the charge density on the plates.

1. $d\sigma/dt = I$
2. $\pi R^2 d\sigma/dt = I$
3. $d\sigma/dt = \pi R^2 I$
4. Something else

Note:
* Correct Answer: B

</section>

<section data-markdown>

We found the relationship between the current and the change of the charge density was: $\pi R^2 d\sigma/dt = I$. Determine the rate of change of the electric field between the plates, $d\mathbf{E}/dt$.

1. $\sigma/\varepsilon_0 \hat{x}$
2. $I/(\pi R^2 \varepsilon_0) \hat{x}$
3. $-I/(\pi R^2 \varepsilon_0) \hat{x}$
4. $I/(2 \pi R \varepsilon_0) \hat{x}$
5. $-I/(2 \pi R \varepsilon_0) \hat{x}$

Note:
* Correct Answer: B

</section>

<section data-markdown>

<img src="./images/capacitor_face_on.png" align="left" style="width: 400px";/>

Use the Maxwell-Ampere Law to derive a formula for the manetic at a distance $r<R$ from the center of the plate in terms of the current, $I$.


1. $B=\frac{\mu_0 I}{2\pi r}$
2. $B=\frac{\mu_0 I r}{2\pi R^2}$
3. $B=\frac{\mu_0 I}{4\pi r}$
4. $B=\frac{\mu_0 I r}{4\pi R^2}$
5. Something else entirely

Note:
* Correct Answer: B

</section>

<section data-markdown>

<img src="./images/capacitor_face_on.png" align="left" style="width: 400px";/>

Use the Maxwell-Ampere Law to derive a formula for the manetic at a distance $r>R$ from the center of the plate in terms of the current, $I$.


1. $B=\frac{\mu_0 I}{2\pi r}$
2. $B=\frac{\mu_0 I r}{2\pi R^2}$
3. 0
5. Something else entirely

Note:
* Correct Answer: A

</section>
