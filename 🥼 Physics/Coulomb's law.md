# Coulomb's law
Created: 03-11-2021 04:10

> ### **Abstract:**
> More than 100 years before Thomson and Rutherford discovered the fundamental particles that carry positive and negative electric charges, Charles Augusting de Coulomb mathematically described the force between charged objects.

**Table of Content**

- [[#Concept|Concept]]
- [[#Using Coulomb's Law to find the force between charged objects.|Using Coulomb's Law to find the force between charged objects.]]
	- [[#Problem|Problem]]
	- [[#Strategy|Strategy]]
	- [[#Solution|Solution]]
- [[#References|References]]


## Concept
The French scientist [[Charles Augustin de Coulomb]] mathematically described the force between charged objects. In order to measure this, he built a device called a [[_torsion balanc|torsion balance]].

![[Pasted image 20211103041533.png]]
From measurements obtained by the torsion balance, he deduced that the electrical force between the two spheres in the balance, was inversely proportional to the distance squared between the spheres:

$$F\ \alpha\ \frac{1}{r^2}$$

Where $r$ is the distance between the spheres.

He also deduced that the force is proportional to the charge on each sphere:

$$F\ \alpha\ q_Aq_B$$

Combining these two proportions, he proposed the following expression to describe the force between the charged spheres:

$$F=k\frac{q_1q_2}{r^2}$$

This equation is known as [[_coulomb's law|Coulomb's law]], and it describes the electrostatic force between charged objects. The constant $K$ is called *coulomb's constant*. In SI units, the constant $K$ has the value $K=8.99\cdot 10^9Nm^2/C^2$.

$K$ is also known as the constant of proportionality and is taken as:
$$K=\frac{1}{4\pi\varepsilon_0}$$

Where $\varepsilon_0$ is a constant known as the permittivity of free space. Coulomb's law can therefore be given as:
$$F=\frac{q_1q_2}{4\pi\varepsilon_0r^2}$$

The direction of the force is along the line joining the centers of the two objects. If the two charges are of opposite signs, Coulomb's law gives a negative result. This means that the force between the particles is attractive. If the two charges have the same signs, Coulomb's law give a positive result which means that the force between them is repulsive.

![[Pasted image 20211103043421.png]]

Note that Coulomb's law applies only to charged objects that are not moving with respect with each other.

> **Coulomb's law states that**:
> *The force between two electrically charged bodies is proportional to the amount of charge on each object and inversely proportional to the square of the distance between the two bodies.*
> $$F=K\frac{q_1q_2}{r^2}$$

Coulomb's law is an example of an [[_inverse-square law|inverse square law]] which means the force depends on the square of the denominator.

## Using Coulomb's Law to find the force between charged objects.

### Problem
An engineer measures the force between two ink drops by measuring their acceleration and their diameter. She finds that each member of a pair of ink drops exert a repulsive force $F=5.5mN$ on its partner. If each ink drop carries a charge $q_{inkdrop}=1\cdot10^{-10}C$, how far apart are the ink drops?

### Strategy
We know the force and the charge on each ink drop, so we can use [[_coulomb's law|Coulomb's law]] for the distance $r$ between the ink drops.

### Solution
The charges in Coulomb's law are $q_1=q_2=q_{inkdrop}$, so the numerator in coulomb's law takes the form $q_1q_2=q_{inkdrop}{2}$.
Inserting this into Coulomb's law and solving for the distance $r$ gives.

$$F=\frac{kq^2_{inkdrop}}{r^2}$$
$$r = \sqrt{\frac{kq^2_{inkdrop}}{F}}$$
$$=\pm \sqrt{\frac{(8.99\cdot10^{9}N\cdot m^2/C^2)(-1\cdot10^{-10}C)^2}{5.5\cdot10^{-3}N}}$$
$$\pm 1.3\cdot10^{-4}m$$

## References
1. 