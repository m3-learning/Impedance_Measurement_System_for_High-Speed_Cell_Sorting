# Impedance_Measurement_System_for_High-Speed_Cell_Sorting

This PCB can be mounted on a National Instruments PXI with a PXI-5412 arbitrary waveform generator and a PXIe-5122 Oscilloscope or similar module with R<sub>ref;</sub>. The voltage across R<sub>ref;</sub> and the entire circuit can be used to calculate impedance with the [I-V method][1] according to the following equation

 
![\Large Zx=\frac{-b\pm\sqrt{b^2-4ac}}{2a}](https://latex.codecogs.com/svg.latex?\Large&space;\color{white}{Z_{x}=\frac{V_{A2}}{I}=\frac{V_{A2}}{V_{A1}-V_{A2}}R_{ref})



<img src="https://github.com/m3-learning/Impedance_Measurement_System_for_High-Speed_Cell_Sorting/blob/main/renders/schematic.PNG" alt="drawing" width="400"/>

<img src="https://github.com/m3-learning/Impedance_Measurement_System_for_High-Speed_Cell_Sorting/blob/main/renders/impedance_pcb.PNG" alt="drawing" width="650"/>

<img src="https://github.com/m3-learning/Impedance_Measurement_System_for_High-Speed_Cell_Sorting/blob/main/renders/pxi_mounted_impedance.PNG" alt="drawing" width="650"/>


[1]: https://assets.testequity.com/te1/Documents/pdf/impedance-measurement-handbook.pdf#page=23
