# Impedance_Measurement_System_for_High-Speed_Cell_Sorting

This impedance measurement PCB can be mounted on a National Instruments PXI System with a PXI-5412 arbitrary waveform generator and a PXIe-5122 Oscilloscope or similar modules. The voltage across R<sub>ref</sub> and the entire circuit can be used to calculate impedance with the 
<a href="https://assets.testequity.com/te1/Documents/pdf/impedance-measurement-handbook.pdf#page=23" target="_blank">I-V method</a>
 according to the following equation.

 
![](https://latex.codecogs.com/svg.latex?\Large&space;\color{white}{Z_{x}=\frac{V_{A2}}{I}=\frac{V_{A2}}{V_{A1}-V_{A2}}R_{ref})

The Inventor part "spacer1" can be used to offset the SMB female socket.


<img src="https://github.com/m3-learning/Impedance_Measurement_System_for_High-Speed_Cell_Sorting/blob/main/renders/schematic.PNG" alt="drawing" width="360"/>

<img src="https://github.com/m3-learning/Impedance_Measurement_System_for_High-Speed_Cell_Sorting/blob/main/renders/impedance_pcb.PNG" alt="drawing" width="650"/>

<img src="https://github.com/m3-learning/Impedance_Measurement_System_for_High-Speed_Cell_Sorting/blob/main/renders/pxi_mounted_impedance.PNG" alt="drawing" width="650"/>