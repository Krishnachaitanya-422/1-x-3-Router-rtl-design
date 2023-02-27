# 1-x-3-Router-rtl-design
This Repository consists of the verilog code and test bench for the design of 1 x 3 router with output wave forms also.

This router architecture consists of 4 submodules
1. FSM
2. SYNC
3. REGISTER
4. FIFO

This is a 1x3 router where there will be one source and 3 destinations and data to the destination can be sent using the address of the destination in the payload

the structure of payload is as follows:

size of payload bytes | address  }--> header
________________________________
.
.
.
.
.                                }-->payload           
.
.
.
_________________________________
parity byte                      }-->parity   



The outputs of TOPmodule is as follows:


![router top module rtl design](https://user-images.githubusercontent.com/66372002/221495935-6a971b9a-ea97-4553-a5fc-cff5f61f4fc9.PNG)



![ROUTER TOP MODULE DUT WAVEFORMS](https://user-images.githubusercontent.com/66372002/221495978-625346fa-5fd4-4107-b5cf-5ee0a5e4751f.PNG)



![ROUTER TOP MODULE MONITOR OUTPUT](https://user-images.githubusercontent.com/66372002/221496094-f4ec1a40-405c-42d0-a285-05b7588b006f.PNG)



![ROUTER TOP MODULE TB WAVE FORMS](https://user-images.githubusercontent.com/66372002/221496132-7c5f3021-27a1-4db2-8255-4c8d631eed79.PNG)







