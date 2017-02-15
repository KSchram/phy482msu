---
layout: slide
theme: white
transition: slide
---

<section data-markdown>

Ampere's Law relates the line integral of B around some closed path, to a current flowing through a surface bounded by the chosen closed path.

$\oint \mathbf{B} \cdot d\mathbf{l} =  \mu_0 I$

By calling it a "Law", we expect that:

1. It is neither correct nor useful.
2. It is sometimes correct and sometimes easy to use.
3. It is correct and sometimes easy to use.
4. It is correct and always easy to use.
5. None of the above.

Note:
* Correct Answer: C

</section>

<section data-markdown>

## Announcements
* Quiz 3 (Friday 2/17) - RLC circuits
  * Solve a circuit problem using the phasor method
  * Discuss limits on the response and how it might act as a filter
* DC out of town tomorrow; back Wed. morning
  * We will have class and I should make it in time
  * I'll message Piazza if there's a problem

</section>

<section data-markdown>

Take the divergence of the curl of any (well-behaved)
vector function $\mathbf{F}$, what do you get?

$$\nabla \cdot \left(\nabla \times \mathbf{F}\right) = ???$$

1. Always 0
2. A complicated partial differential of $\mathbf{F}$
3. The Laplacian: $\nabla^2 \mathbf{F}$
4. Wait, this vector operation is ill-defined!

Note:
* Correct Answer: A

</section>

<section data-markdown>

Take the divergence of both sides of Faraday's law:

$$\nabla \times \mathbf{E} = -\dfrac{\partial \mathbf{B}}{\partial t}$$

What do you get?
1. 0 = 0 (is this interesting?)
2. A complicated partial differential equation (perhaps a wave equation of some sort ?!) for $\mathbf{B}$
3. Gauss’ law!
4. ???

Note:
* Correct Answer: A
</section>

<section data-markdown>

Take the divergence of both sides of Ampere's law:

$$\nabla \times \mathbf{B} = \mu_0 \mathbf{J}$$

**According to this**, the divergence of $\mathbf{J}$ is:


1. $-\partial \rho/\partial t$
2. A complicated partial differential of $\mathbf{B}$
3. Always 0
4. ???

Note:
* Correct Answer: C
</section>

<section data-markdown>

Ampere's Law relates the line integral of $\mathbf{B}$ around some closed path, to a current flowing through a surface bounded by the chosen closed path.

$\oint \mathbf{B} \cdot d\mathbf{l} =  \mu_0 I$

The **path** can be:

1. Any closed path
2. Only circular paths
3. Only sufficiently symmetrical paths
4. Paths that are parallel to the B-field direction.
5. None of the above.

Note:
* Correct Answer: A

</section>

<section data-markdown>

Ampere's Law relates the line integral of $\mathbf{B}$ around some closed path, to a current flowing through a surface bounded by the chosen closed path.

$\oint \mathbf{B} \cdot d\mathbf{l} =  \mu_0 I$

The **surface** can be:

1. Any closed bounded surface
2. Any open bounded surface
3. Only surfaces perpendicular to $\mathbf{J}$.
4. Only surfaces tangential to the B-field direction.
5. None of the above.

Note:
* Correct Answer: B

</section>


<section data-markdown>

Rank order $\int \mathbf{J} \cdot d\mathbf{A}$ (over blue surfaces) where $\mathbf{J}$ is uniform, going left to right:

<img src="./images/current_surfaces.png" align="center" style="width: 600px";/>


1. iii > iv > ii > i
2. iii > i > ii > iv
3. i > ii > iii > iv
4. Something else!!
5. Not enough info given!!

Note:
* CORRECT ANSWER: D
* They are all the same!

</section>

<section data-markdown>

We are interested in $\mathbf{B}$ on the dashed "Amperian loop", and plan to use $\oint \mathbf{B}\cdot d\mathbf{l} = \mu_0 I_t$ to figure it out. What is $I_t$ here?

<img src="./images/wire_w_cap.png" align="center" style="width: 700px";/>


1. $I$
2. $I/2$
3. 0
4. Something else

Note:
* Correct Answer: A
</section>

<section data-markdown>

We are interested in $\mathbf{B}$ on the dashed "Amperian loop", and plan to use $\oint \mathbf{B}\cdot d\mathbf{l} = \mu_0 I_t$ to figure it out. What is $I_t$ here? *The surface over which we integrate $\mathbf{J}\cdot d\mathbf{A}$ is shown
 in blue.*

<img src="./images/cap_w_wire_highlighted.png" align="center" style="width: 700px";/>


1. $I$
2. $I/2$
3. 0
4. Something else

Note:
* Correct Answer: A
</section>

<section data-markdown>

We are interested in $\mathbf{B}$ on the dashed "Amperian loop", and plan to use $\oint \mathbf{B}\cdot d\mathbf{l} = \mu_0 I_t$ to figure it out. What is $I_t$ here? *The surface over which we integrate $\mathbf{J}\cdot d\mathbf{A}$ is shown
 in blue.*

<img src="./images/cap_soap_bubble.png" align="center" style="width: 700px";/>


1. $I$
2. $I/2$
3. 0
4. Something else

Note:
* Correct Answer: C
</section>

<section data-markdown>

The complete differential form of Ampere's Law is now argued to be:

$$\nabla \times \mathbf{B} = \mu_0\mathbf{J} + \mu_0 \epsilon_0\dfrac{\partial \mathbf{E}}{\partial t}$$

The integral form of this equation is:

1. $\iint \mathbf{B}\cdot d\mathbf{A} = \mu_0 I + \mu_0 \epsilon_0 \frac{d}{dt}\oint \mathbf{E}\cdot d\mathbf{l}$
2. $\oint \mathbf{B}\cdot d\mathbf{l} = \mu_0 I + \mu_0 \epsilon_0 \frac{d}{dt}\oint \mathbf{E}\cdot d\mathbf{l}$
3. $\iint \mathbf{B}\cdot d\mathbf{A} = \mu_0 I + \mu_0 \epsilon_0 \frac{d}{dt}\iint \mathbf{E}\cdot d\mathbf{A}$
4. $\oint \mathbf{B}\cdot d\mathbf{l} = \mu_0 I + \mu_0 \epsilon_0 \frac{d}{dt}\iint \mathbf{E}\cdot d\mathbf{A}$
5. Something else/???

Note:
* Correct Answer: D

</section>
