# Simple AC Circuits (Fleeting)
Created: 31-10-2021 06:35

**Table of Content**

- [[#Resistor|Resistor]]
- [[#Capacitor|Capacitor]] 
- [[#Inductor|Inductor]]
- [[#References|References]]



The [[_emf|emf]] (electromotive force) of an [[_a.c circuit|a.c circuit]]  is given by:

$$
v(t)=V_0\ sin(\omega t)
$$

In the figure below, a [[_phase constant|phase constant]] may be involved that shifts the function when we start measuring voltages, similar to the phase constant in [[Waves  & Their Properties|waves]].

![[Pasted image 20211031071336.png]]
## Resistor
* Using [[_kirchhoff's loop rule|kirchhoff's loop rule]], the instantaneous voltage across the [[_resistor|resistor]] of the figure below is given as:

$$
v_R(t)=V_0\ sin(\omega t)
$$

and the instantaneous current through the resistor is:

$$ 
i_R(t)=\frac{v_R(t)}{R}=\frac{V_0}{R}\sin(\omega t)=I_0\sin(\omega t)
$$

![[Pasted image 20211031071222.png]]
Here, $I_0=V_0/R$ is the amplitude of the time-varying current. In the image above, both curves reach their [[_maxima|maxima]] and [[_minima|minima]] at the same time which means that both the current and voltage are [[in phase]].

* Graphical representations of the phase relationships between current and voltage are often useful in the analysis of a.c circuits. These diagrams are called [[_phasor diagrams|phasor diagrams]].
* The phasor diagram for $i_R(t)$ below $(a)$, with the current on the vertical axis. The arrow (or phasor) is rotating counterclockwise at a constant [[_angular frequency|angular frequency]], so with the phasor diagram, we are viewing it at one instant in time. If the length of the arrow corresponds to the current amplitude $I_0$, the projection of the rotating arrow onto the vertical axis is $i_R(t)=I_0\ sin(\omega t)$, which is the instantaneous current.

![[Pasted image 20211031072913.png]]
* The vertical axis on the phasor diagram could be either the voltage or the current, depending on the phasor that is being examined.  In $(b)$, both current and voltage have the same frequency and are in phase, their phasors point in the same direction and rotate together. The ratio of the lengths of the two phasors can be represented by the resistance, since one is a voltage phasor and the other is a current phasor.

## Capacitor
![[Screen Shot 2021-10-31 at 1.37.13 PM.png]]

From [[_kirchhoff's loop rule|Kirchhoff's loop rule]], the instantaneous voltage across the the capacitor of $(a)$ in the image above is:

$$instantaneous\ voltage \rightarrow v_C(t)=V_0\sin(\omega t)$$

Recall that the charge in a capacitor is given by $Q=CV$. This is true at any time measured in the a.c cycle of voltage. Consequently, the instantaneous charge on the capacitor is:

$$instantaneous\ charge \rightarrow q(t)=Cv_c(t)=CV_0\sin(\omega t)$$

Since the current in the circuit is the rate at which charge enters (or leaves) the capacitor,

$$i_C(t)=\frac{dq(t)}{dt}=\omega CV_0\cos(\omega t)=I_0\cos(\omega t)$$

Where $I_0=\omega CV_0$ is the current amplitude or [[_peak current|peak current]]. Using the trigonometric relationship $\cos (\omega t)=\sin (\omega t + \frac{\pi}{2})$, we may express the instantaneous current as:

$$instantaneous\ current \rightarrow i_C(t)=I_0\sin(\omega t + \frac{\pi}{2})$$

Dividing $V_0$ by $I_0$, we obtain an equation that looks similar to [[_ohm's law|ohm's law]]:

$$\frac{V_0}{I_0}=\frac{1}{\omega C}=X_C$$



## References
1. https://phys.libretexts.org/Bookshelves/University_Physics/Book%3A_University_Physics_(OpenStax)/Book%3A_University_Physics_II_-_Thermodynamics_Electricity_and_Magnetism_(OpenStax)/15%3A_Alternating-Current_Circuits/15.03%3A_Simple_AC_Circuits