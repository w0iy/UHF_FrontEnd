# UHF_Front End
This is a companion to the Analog Devices ADALM Pluto. 
The device contains wideband Rx Preamp and low power Tx PA for UHF, with T/R switch. This can be built for wide coverage or for a specific band. 

I consider this and adjunct to the Langstone Project:  https://wiki.microwavers.org.uk/Langstone_Project#Discussion_Forum
This is my first of likely many iterations which will improve the utility of the ADALM Pluto.

Users can install whatever RF devices they desire. The active RF device footprints can accommodate SOT89, X pill pack or 4 legged SOT devices, the latter being rotated 45 degrees. 

From the Antenna, there is a simple Panasonic Tx/Rx relay with speciications to 2GHz. On Rx, there is a low noise amplifier using a Qorvo SPF5189Z which is a rather good device. 

On Tx, there can be 1 or 2 MMICs. 

My plan is to have a single BPF on the Antenna side, which will have 2 characteristics: low insertion loss (for NF) and deep stop bands to suppress TV stations. This filter will also serve to suppress the Tx harmonics. This filter is in the early stages of development. (as of summer 2020)

ALWAYS OPEN TO COMMENTS OR SUGGESTIONS!       
Look me up w0iy on QRZ

