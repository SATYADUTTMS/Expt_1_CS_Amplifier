# Expt_1_CS_Amplifier
This file contains the Experiment 1 CS Amplifier files.

MOSFETs or Metal Oxide Semiconductor Field Effect Transistor plays an important role in our day to day life because of its advantages, characteristics and numerous applications.
It can be used as a "Switch" as well as an "Amplifier". These are the 2 primary applications of MOSFETS.
There are different configurations of MOSFETs being used namely 

1.Common Source Amplifier (CS)

2.Common Gate Amplifier   (CG)

3.Common Drain Amplifier  (CD)

Out of which Common Source Amplifier has an advantage as offers a high voltage gain, good input impedance, and a relatively low output impedance compared to Common Gate and Common  Drain .

The below is the general representation of a CS Amplifier.

![Image](https://github.com/user-attachments/assets/b4af6e83-4f0e-43cd-bf48-05dd4049256e)

We observe that it consists of an NMOS ( N Channel MOSFET ) , whose gate terminal is connected with the Input voltage, the Vin applied has to be greater than the threshold voltage for the channel to form such that the current flows( drain ).

In order to supply power for the circuit , a DC Power supply has been provided at the drain terminal. The Source terminal is connected to the ground.

The drain current flows from supply to the source.Here the applied input is a voltage and we are interested to find the Output Voltage which is been amplified.

Since the MOSFET is a voltage controlled Current device , the output is the drain current. To convert this current to voltage. By Ohm's Law we observe V= I * R. Thus by applying a Resistor at the drain terminal converts this drain current to voltage.

Thus from the Output curves we know that the amplifier works in Saturation Region of MOSFET.

![Image](https://github.com/user-attachments/assets/355e4f53-38ff-442c-b070-0b76902e7f58)

A Q-point (quiescent point) is set in a MOSFET to ensure it operates within its optimal region, providing the desired level of amplification and minimizing distortion and providing a stable DC operating point and also allowing for the largest possible signal swing without clipping or entering non-linear regions.




