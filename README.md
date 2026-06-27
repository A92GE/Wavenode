
# Wavenode
Wavenode WN-2d to Thetis Bridge

Allows data from WN-2d to be used in Thetis Multimeter I/O, and allows Thetis to control WN-2d logic outputs and reset SWR trip

Automatic selection of Wavenode sensors by band

## Screenshot

1![Wavenode](Screenshots/Screenshot_v_1_8.png)

The Thetis Network Settings to correspond with the above screenshot would be as follows:

<img width="746" height="547" alt="Thetis Network Settings" src="https://github.com/user-attachments/assets/2415ee5e-f4f5-4413-a28e-ed6d7ecb1b9f" />

The Thetis Multimeter I/O settings are as follows:

<img width="746" height="546" alt="Thetis Multimeter IO" src="https://github.com/user-attachments/assets/7ff1f75d-2849-49fe-88ad-b5049aad76b3" />

The Thetis Meters/Gadgets can then be used to display the data as required. 

The commands for buttons to switch the digital outputs are:
  {"command":"swr_reset"}
  {"out1": true} {"out1": false}
  {"out2": true} {"out2: false}
  {"out3": true} {"out3": false}
  {"out4": true} {"out4": false}
