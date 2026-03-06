# Diode Clipper Simulation

Name:Nelson E Ndu

AC Source: SINE(0 10 50)  
Transient Analysis: .tran 40ms

Analysis:
The input voltage is a sinusoidal waveform with a peak amplitude of 10 V and frequency of 50 Hz.
The diode limits the output voltage when the input exceeds the diode's forward voltage (approximately 0.7 V). During the positive half cycle, the diode conducts and clamps the output voltage. During the negative half cycle, the diode is reverse biased and the output follows the input signal.
This demonstrates the clipping behavior of a diode limiter circuit.
