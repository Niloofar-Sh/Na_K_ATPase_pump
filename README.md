# Na_K_ATPase_pump
Na+/K+ ATPase Pump model originally created by Michael Pan in CellML format. The equivalent BGT model is provided in this repository.
The CellML model is also uploaded for further reference.
For the voltage clamp test of the pump, a new component was added to BGT to increase the charge amount of the membrane capacitance step by step.
The electrical capacitor component in BGT has the constitutive relation of dq_0-f_0 while in the CellML file we have dq_0=153.4 (0.001*C_m).
C_mem was added to BGT with the constitutive relation of dq_0-153.4
