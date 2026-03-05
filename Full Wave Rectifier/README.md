# Full Wave Rectifier

# Simulation Settings
AC Source: SINE(0 100 50)  
Transient Analysis: .tran 40ms

# Sweep Range
Simulation time: 40 ms (two cycles of a 50 Hz signal)

# Analysis
The input voltage is a sinusoidal waveform with a peak amplitude of 100 V and frequency of 50 Hz. 

The full-wave rectifier converts both the positive and negative half cycles of the AC input into positive output pulses. This results in a rectified waveform with a frequency of 100 Hz, which is twice the input frequency. The output voltage is slightly lower due to the voltage drop across the conducting diodes.
