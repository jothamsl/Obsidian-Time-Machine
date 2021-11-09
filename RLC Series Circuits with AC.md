# RLC Series Circuits with AC
Created: 09-11-2021 05:06

> ### **Abstract:** In this note we learn what RLC circuits are, how they work and the formulas governing how they behave.

The a.c circuit shown below, called an *RLC* series circuit, is a series of combination of a resistor, capacitor and inductor connected across an a.c source. It produces an emf of

$$v(t)=V_0 \sin \omega t$$

![[Pasted image 20211109050826.png]]

The relative phase between the current and the emf is not obvious when all three elements are present. Consequently, we represent the current by the general expression:

$$i(t)=I_0\sin(\omega t-\phi)$$
Where $I_0$ is the current amplitude and $\phi$ is the **phase angle** between the current and the applied voltage. The phase angle is thus the amount by which the voltage and current are out of phase with each other in a circuit. 

## TODO: PHASOR DIAGRAM

We can easily determine the unknown quantities $I_0$ and $\phi$ from the geometry of the phasor diagram. For the phase angle:
$$\phi=\tan^{-1}\frac{V_L-V_C}{V_r}=\tan^{-1}\frac{I_0X_L-I_0X_C}{I_0R}$$
We then get:
$$\phi=\tan^{-1}\frac{X_L-X_C}{R}$$

Furthermore from the pythagorea


## References
1. 