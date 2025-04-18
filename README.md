# single-phase-full-bridge-inverter-circuit
a single phase full bridge inverter circuit and use Arduino to generate switching pulses/ signals. Observe the output waveform, measure its RMS, frequency and harmonic component.Now use any PWM technique to make RMS variables. Also observe the effect of PWM on the harmonic content of the waveform. Verify the results using any simulation software

Excessive usage of naturally available reservoirs for power generation is exponentially depleting
these reservoirs. This has forced the researchers to shift towards renewable energy sources like
solar energy, wind energy etc. Power generated through these sources is stored in the batteries for
the usage when required. Next step in this process is to convert the DC voltage stored in batteries
to AC for utilization at homes and industries.
Inverters are the power electronic circuits that convert DC voltage into AC of desired frequency
and RMS. Commonly used are the single phase half bridge, single phase full bridge and three
phase bridge inverters.
Figure 1 shows the single phase full bridge inverter. Gate signals are applied in such a manner
that the transistors Q1 and Q2 turn ON simultaneously while at the same instant Q3 and Q4 turn
OFF making the output voltage equal to and current . Similarly at the instant where transistors
Q1 and Q2 turn OFF, transistors Q3 and Q4 abruptly turn ON making the output voltage while
the current is .

![image](https://github.com/user-attachments/assets/1527361f-b48e-487b-8d70-9a0f4ad9f4d2)

# Single Phase Inverter Circuits

Single Phase Half-bridge Inverter: A single-phase half-bridge inverter is a simpler form of an inverter that converts DC to AC. It uses two switching devices and typically requires a split DC power supply or a capacitor divider to provide the necessary voltage levels.
# Components

●	Two Switching Devices: Often MOSFETs or IGBTs.

●	DC Power Supply: Split into two equal voltages, or a single supply with a center tap or capacitor divider.
●	Filter: To smooth the output waveform.

# Operation

●	The inverter alternates between two states:

○	In the first state, one switch is on, and the other is off, allowing the first half of the DC supply to drive the load.
○	In the second state, the switches are reversed, allowing the second half of the DC supply to drive the load.
●	This produces an AC waveform with a maximum output voltage equal to half the DC supply voltage.
Output

●	The output is a square wave, which can be filtered to approximate a sine wave.



●	Harmonics are higher compared to a full-bridge inverter.


# Single Phase Full-Bridge Inverter:
A single-phase full-bridge inverter is more complex than the half-bridge inverter. It uses four switching devices to convert DC to AC and can produce a higher output voltage.
Components


●	Four Switching Devices: Typically MOSFETs or IGBTs.

●	Single DC Power Supply: No need for a split power supply.

●	Filter: To smooth the output waveform.

# Operation

●	The inverter operates by alternating pairs of switches:

○	In the first state, two diagonal switches are on, creating a positive output voltage.

○	In the second state, the other diagonal pair of switches are on, creating a negative output voltage.
●	This produces an AC waveform with a maximum output voltage equal to the DC supply voltage.
# Output

●	The output is a square wave, similar to the half-bridge inverter, but with a higher voltage.

●	Harmonics are present, but can be reduced using techniques like PWM.




We are required to use a single phase full bridge converter in our task, so that is what we will be using to design our circuit on both; hardware and software.

# Simulation:

●	By using Simulink we will model the inverter circuit.

●	Validating the hardware results with simulated waveforms and parameters.



![image](https://github.com/user-attachments/assets/893ccb29-988a-4521-a69d-e97ecafe9002)

![image](https://github.com/user-attachments/assets/953581f0-82b3-4f0b-9c1e-c16c3501b8a8)

