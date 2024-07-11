# Design-and-implementation-of-current-starved-VCO-FOR-PLL
Designing a linear and wide-range voltage-controlled oscillator for RF
application in the VLSI field is challenging for Electronics Engineers. VCO is the main component in 
many RF circuits. VCO is the heart of the Phase Lock Loop system. An oscillator is an autonomous
system that generates a periodic output without input. The VCO is an electronic circuit
that produces the frequency signal depending on its input voltage. VCO is a voltage-to-frequency converter. The Barkhausen criteria for oscillation can be met without resonators as in
ring oscillators. If the open loop circuit exhibits sufficient gain at the zero phase frequency,
oscillations occur. The important requirements of VCO are Frequency accuracy, wide tuning
range, tuning linearity, low power consumption, small size, and low phase noise
## DIFFERENT ARCHITECTURES OF VCO
### LC VCO
These VCOs are typically constructed using inductors, capacitors, and an amplifier. They generate high-frequency voltage-controlled oscillations, making them suitable for applications requiring sinusoidal wave output. This architecture is particularly advantageous in situations where space constraints are not critical.
### Source Coupled VCO
These VCOs are constructed using transistors arranged in a back-to-back configuration, which enables the generation of high-frequency oscillations. They are versatile enough to produce rectangular and sawtooth waveforms as well. Compared to current-starved VCOs, these designs can achieve lower power dissipation. However, a significant drawback is their reliance on capacitors, which may pose challenges in single-poly pure digital processes due to potential parasitic effects.

