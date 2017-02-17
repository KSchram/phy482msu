---
layout: slide
theme: white
transition: slide
---

<section data-markdown>

How amazing is that $\dfrac{1}{\sqrt{\epsilon_0 \mu_0}} = 3\times10^8 \mathrm{m/s}$?

1. OMGBBQPIZZA, so amazing!
2. It's pretty cool
3. Meh
4. Whatever

</section>

<section data-markdown>
## Correct Answer
OMGBBQPIZZA, so amazing!

</section>

<section data-markdown>

What do you want to do today?
1. Clickers and lecture
2. Tutorial

*Either way, we are covering the same example.*

</section>

<section data-markdown>

Consider a large parallel plate capacitor as shown, charging so that $Q = Q_0+\beta t$ on the positively charged plate. Assuming the edges of the capacitor and the wire connections to the plates can be ignored, what is the direction of the magnetic field $\mathbf{B}$ halfway between the plates, at a radius $r$?

<img src="./images/charging_cap_dEdt.png" align="left" style="width: 400px";/>

1. $\pm \hat{\phi}$
2. 0
3. $\pm \hat{z}$
4. $\pm \hat{s}$
5. ???

Note:
* Correct Answer: A

</section>

<section data-markdown>

Same capacitor with $Q = Q_0+\beta t$ on the positively charged plate. What is the direction of the magnetic field $\mathbf{B}$ halfway between the plates, at a radius $r$?

<img src="./images/charging_cap_dEdt.png" align="left" style="width: 400px";/>

1. $+\hat{\phi}$
2. $-\hat{\phi}$
3. Not sure how to tell

Note:
* Correct Answer: A

</section>

<section data-markdown>

Same capacitor with $Q = Q_0+\beta t$ on the positively charged plate. What kind of amperian loop can be used between the plates to find the magnetic field $\mathbf{B}$ halfway between the plates, at a radius $r$?

<img src="./images/charging_cap_dEdt_loop.png" align="center" style="width: 500px";/>

D) A different loop  E) Not enough symmetry for a useful loop

Note:
* Correct Answer: B
</section>

<section data-markdown>

Same capacitor with $Q = Q_0+\beta t$ on the positively charged plate. What is the magnitude of the magnetic field $\mathbf{B}$ halfway between the plates, at a radius $r$?

<img src="./images/charging_cap_dEdt_smaller.png" align="left" style="width: 400px";/>

1. $\frac{\mu_0 \beta}{2 \pi r}$
2. $\frac{\mu_0 \beta r}{2 d^2}$
3. $\frac{\mu_0 \beta d}{2 a^2}$
4. $\frac{\mu_0 \beta a}{2 \pi r^2}$
5. None of the above

Note:
* Correct Answer: E

</section>

<section data-markdown>

<img src="./images/cap_plates_boxed.png" align="right" style="width: 400px";/>

Consider the surface of an imaginary volume (dashed lines, at right) that partly encloses the left capacitor plate. For this closed surface, is the total flux of the current density, $\iint \mathbf{J} \cdot d\mathbf{A}$ positive, negative or zero?



1. Positive
2. Negative
3. Zero

Note:
* Correct Answer: B
* The charge density is increasing, so the total charge in the region is increasing with time, thus the flux of the current density must be negative (conservation of charge).
</section>


<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>


At each location, we will evaluate the sign of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$.

**At location 3**, the signs of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$ are:
1. both zero
2. both negative
3. both positive
4. $\partial \rho/\partial t$ is positive and $\nabla \cdot \mathbf{J}$ is negative
5. $\partial \rho/\partial t$ is negative and $\nabla \cdot \mathbf{J}$ is positive

*Recall that charge is conserved locally!*

Note:
* Correct Answer: A
* There is no current or charge inthe region

</section>

<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>


At each location, we will evaluate the sign of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$.

**At location 2**, the signs of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$ are:
1. both zero
2. both negative
3. both positive
4. $\partial \rho/\partial t$ is positive and $\nabla \cdot \mathbf{J}$ is negative
5. $\partial \rho/\partial t$ is negative and $\nabla \cdot \mathbf{J}$ is positive

*Recall that charge is conserved locally!*

Note:
* Correct Answer: D
* One way to think about this is that the charge on the plate is increasing (so the density is increasingly more positive - positive charge). So the divergence of the current density is negative (jives with previous CQ also).

</section>

<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>


At each location, we will evaluate the sign of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$.

**At location 4**, the signs of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$ are:
1. both zero
2. both negative
3. both positive
4. $\partial \rho/\partial t$ is positive and $\nabla \cdot \mathbf{J}$ is negative
5. $\partial \rho/\partial t$ is negative and $\nabla \cdot \mathbf{J}$ is positive

*Recall that charge is conserved locally!*

Note:
* Correct Answer: E
* One way to think about this is that the charge on the plate is increasing (so the density is increasingly more negative - negative charge). So the divergence of the current density is positive.

</section>

<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>


At each location, we will evaluate the sign of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$.

**At location 1**, the signs of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$ are:
1. both zero
2. both negative
3. both positive
4. $\partial \rho/\partial t$ is positive and $\nabla \cdot \mathbf{J}$ is negative
5. $\partial \rho/\partial t$ is negative and $\nabla \cdot \mathbf{J}$ is positive

*Recall that charge is conserved locally!*

Note:
* Correct Answer: A
* The divergence of the curl of the magnetic field is zero and there's no electric field out there, so the divergence of J must vanish.

</section>


<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>


At each location, we will evaluate the sign of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$.

**At location 5**, the signs of $\partial \rho/\partial t$ and $\nabla \cdot \mathbf{J}$ are:
1. both zero
2. both negative
3. both positive
4. $\partial \rho/\partial t$ is positive and $\nabla \cdot \mathbf{J}$ is negative
5. $\partial \rho/\partial t$ is negative and $\nabla \cdot \mathbf{J}$ is positive

*Recall that charge is conserved locally!*

Note:
* Correct Answer: A
* The divergence of the curl of the magnetic field is zero and there's no electric field out there, so the divergence of J must vanish.

</section>

<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>

Suppose the original Ampere's law $\nabla \times \mathbf{B} = \mu_0\mathbf{J}$ were correct without any correction from Maxwell (it’s not, but suppose for a moment that it is). What would this imply about $\nabla \cdot \mathbf{J}$ at points 2 and 4 in the diagram?

1. The remain unchanged
2. They swap signs
3. They become zero
4. ???

Note:
* Correct Answer: C


</section>

<section data-markdown>

<img src="./images/5_locations_charging_cap.png" align="left" style="width: 400px";/>

Let's continue with the (incomplete) definition of Ampere's Law: $\nabla \times \mathbf{B} = \mu_0\mathbf{J}$.

What does this form tell you about the signs of $(\nabla \times \mathbf{B})_x$ at locations 1, 3, and 5?

1. All positive
2. All negative
3. Positive at 1 and 5, zero at 3
4. Negative at 1 and 5, zero at 3
5. Something else


Note:
* Correct Answer: C
* All we need here is the direction of Jx, which is zero at 3
</section>

<section data-markdown>
