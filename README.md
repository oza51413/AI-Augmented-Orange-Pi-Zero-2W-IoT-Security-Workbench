# AI-Augmented-Orange-Pi-Zero-2W-IoT-Security-Workbench

- Usage: AI gets access to the pi through ssh
  - project folder for the AI to access
  - sub folders /Recon, /Foothold, /RevEng  
  - AI gets access to the hardware
 
  
1. Recon
  - images of the device  
  
2. Foothold
  - signal analysis/interposition
  - protos: uart,i2c,jtag

3. RevEng
  - tools: wairz, claude

  

# Parts List

1. Orange Pi Zero 2w
  - UART connected through pi's pins

2. USB Hat    
  - allows for usage of logic analyzer + flash programmer    
  - Alfa wifi card (packet injection)
  - Nordic NRF BLE Sniffer  

3. 5v Relay    
  - safety precaution, not trying to fry the pi
  - connects to pi's pins   

4. Mini Bread Board
  - used to mount all of the components
