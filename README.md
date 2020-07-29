# UHF_FrontEnd
A wideband Rx Preamp and low power Tx PA for UHF, with T/R switch. This can be built for wide coverage or foa a specific band.

I consider this and adjunct to the Langstone Project:  https://wiki.microwavers.org.uk/Langstone_Project#Discussion_Forum
This is my first of likely many iterations which will improve the utility of the ADALM Pluto.

From the Antenna, there is a simple mechanical Tx/Rx relay. On Rx, there is a low noise amplifier using a Qorvo SPF5189Z which is a rather good device. 
On Tx, there is a GALI-74+ which provides about +25db of gain. There is provision for another gain stage using a MOSFET AFT05M (there is a family). The low
power device is in a SOT-89. The components are a direct copy from the AFT05M evaluation board.

My plan is to have a single BPF on the Antenna side, which will have 2 characteristics: low insertion loss (for NF) and deep stop bands to suppress TV stations. This filter will also serve to suppress the Tx harmonics. This filter is in the early stages of development. (as of summer 2020)

