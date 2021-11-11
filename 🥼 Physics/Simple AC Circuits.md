# Simple AC Circuits
Created: 09-11-2021 03:23

> ### **Abstract:**

**Table of Content**

- [[#R.m.s Current & Voltage|R.m.s Current & Voltage]]
- [[#Resistor|Resistor]]
- [[#Capacitor|Capacitor]]
- [[#Inductor|Inductor]]
- [[#References|References]]
- [[#References|References]]


## R.m.s Current & Voltage

If we were to average out the values of current or voltage, these values are zero. Because of this, we often use a second convention called the root mean square value, or *rms* value.

The *rms* operates in reverse of the terminology. First, you square the function, then you find the mean, and then you find the square root. As a result, the *rms* values of current and voltage are not zero. Appliances and devices are commonly quoted with *rms* values for their operations, rather than peak values.

The *rms* value of an a.c circuit is denoted as: $I_{rms}$ or $V_{rms}$.

The *rms* current $I_{rms}$ is given as:
$$I_{rms}=\frac{I_0}{\sqrt{2}}$$
Where $I_0$ is the peak current in an a.c system

The *rms* voltage $V_{rms}$ is given as:
$$V_{rms}=\frac{V_0}{\sqrt{2}}$$
Where $V_0$ is the peak voltage in an a.c system.


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

The quantity $X_C$ is analogous to resistance in a [[_direct current|d.c]] circuit in the sense that both quantities are a ratio of a voltage to a current. As a result, they have the same unit, the ohm. Keep in mind, that a capacitor stores and discharges electric energy, whereas a resistor dissipates it. The quantity $X_C$ is known as the **capacitive reactance** of the capacitor, or the opposition of a capacitor to a change in current. It depends inversely on the frequency of the a.c source - high frequency leads to low capacitive reactance.

A comparison of the expressions for $v_C(t)$ and $i_C(t)$ shows that there is a [[_phase|phase]] difference of $\pi/2$ rad between them. When these two quantities are plotted together, the current peaks a quarter cycle (or $\pi/2$ rad) ahead of the voltage. 

The current through a capacitor leads the voltage across a capacitor by $\pi/2$ rad, or a quarter of a cycle.

In a capacitive a.c circuit, the *rms* current appears because the voltage is continually reversing, charging and discharging the capacitor. 

If the frequency goes to zero, which would be a d.c voltage, $X_C$ tends to infinity, and the current is zero once the capacitor is charged. At very high frequencies, the capacitor's reactance tends to zero - it has a negligible reactance and does not impede the current (it acts like a simple wire)

## Inductor

From [[_kirchhoff's loop rule|Kirchhoff's loop rule]], the voltage across the inductor $L$ is:
$$v_L(t)=V_0\sin(\omega t)$$

THe emf across an inductor is equal to $\epsilon=-L(di_L/dt)$; however, the potential difference across the inductor is $v_L(t)=Ldi_L(t)/dt$, because if we consider that the voltage around the loop must equal zero, the voltage gained from the a.c source must dissipate through the inductor. Therefore, connecting this with the a.c voltage source, we have:

$$\frac{di_L(t)}{dt}=\frac{V_0}{L}\sin (\omega t)$$

![[Pasted image 20211109041516.png]]
The current $i_L(t)$ is found by integrating this equation. Since the circuit does not contain a source of constant [[_emf|emf]], there is no steady current in the circuit. Hence, we can set the constant of integration, which represents the steady current in the circuit, equal to zero, and we have:

$$i_L(t)=-\frac{V_0}{\omega L}\cos (\omega t)=\frac{V_0}{\omega L}\sin (\omega t-\frac{\pi}{2})=I_0\sin (\omega t-\frac{\pi}{2})$$

Where $I_0=V_0/\omega L$. The relationship between $V_0$ and $I_0$ may also be written in a form analogous to [[_ohm's law|Ohm's law]]:

$$\frac{V_0}{I_0}=\omega L=X_L$$ ^022d84

The quantity $X_L$ is known as the **inductive reactance** of the inductor, or the opposition of an inductor to a change in current; its unit is also the ohm. Note that $X_L$ varies directly as the frequency of the a.c source - high frequency causes high inductive reactance.

A phase difference of $\pi/2$ rad occurs between the current and the voltage across the inductor. The current through an inductor lags the potential difference across an inductor $\pi/2$ rad, or a quarter of a cycle
 
## References
1. https://phys.libretexts.org/Bookshelves/University_Physics/Book%3A_University_Physics_(OpenStax)/Book%3A_University_Physics_II_-_Thermodynamics_Electricity_and_Magnetism_(OpenStax)/15%3A_Alternating-Current_Circuits/15.03%3A_Simple_AC_Circuits

## References
1. 