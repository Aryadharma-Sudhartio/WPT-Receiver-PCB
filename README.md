# WPT-Receiver-PCB
This PCB is made as receiver side of WPT system receiving power transferred from transmitter coil, in this PCB there is LCC compensation, Full bridge rectifier, MOSFET driver circuit, Synchronous buck converter, microcontroller signal, and feedback circuit to achive constant current (CC) dan constant voltage (CV).
<img width="862" height="547" alt="image" src="https://github.com/user-attachments/assets/ce15acf8-1741-478f-a82b-207658253499" />

Many polygon with vias stitching are used as tracks in PCB to minimize resistance and distribute power evenly, especially in power stage circuit.

For feedback, the signal tracks are used as short as possible to minimize noise that can disrupt sensor read, resulting in bad system control.
