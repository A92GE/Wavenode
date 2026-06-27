
# Wavenode
Wavenode WN-2d to Thetis Bridge

Allows data from WN-2d to be used in Thetis Multimeter I/O, and allows Thetis to control WN-2d logic outputs and reset SWR trip

Sensor S1 is always active in selected bands. Purpose to monitor transceiver output (input into linear)
Sensors S2-4 are automatically selected by band (only one can be active at a time) corresponding to the three outputs from a linear

## Screenshot

<img width="835" height="547" alt="screenshot_2 0" src="https://github.com/user-attachments/assets/1575cd6f-4c87-417d-a8f2-ed8ee2df6442" />

The Thetis Network Settings to correspond with the above screenshot would be as follows:

<img width="746" height="547" alt="Thetis Network Settings" src="https://github.com/user-attachments/assets/2415ee5e-f4f5-4413-a28e-ed6d7ecb1b9f" />

The Thetis Multimeter I/O settings are as follows:

<img width="746" height="546" alt="Thetis Multimeter IO" src="https://github.com/user-attachments/assets/7ff1f75d-2849-49fe-88ad-b5049aad76b3" />

The Thetis Meters/Gadgets can then be used to display the data as required. A sample Gadget file is included:


<img width="266" height="641" alt="Sample Thetis Gadget" src="https://github.com/user-attachments/assets/93c809c0-9320-4cc7-bca7-09f74136ded0" />


The commands for buttons to switch the digital outputs are:
  
  {"command":"swr_reset"}
  {"out1": true} {"out1": false}
  {"out2": true} {"out2: false}
  {"out3": true} {"out3": false}
  {"out4": true} {"out4": false}
