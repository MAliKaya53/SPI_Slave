# SPI_Slave
The aims of the project is implementation SPI slave Communication protocols using an example of Hardware Description Language: VHDL. 

# Structure
Inputs:
Clock signal, Master-out Slave-in (MOSI), ss (Slave Select)

SPI communication can be implemented using state or timed state machines. 
I selected state machine 

Firstly, draw State Machine Diagram (Moore State Machine):
There are 8 situations
![diagram](https://github.com/MAliKaya53/SPI_Slave/assets/83914338/99f86f1b-5a68-43a1-8f89-af096b53650e)

And, waveform
you can understand clearly, if you examine waveform before look up the simulation
![wave_form](https://github.com/MAliKaya53/SPI_Slave/assets/83914338/9c2e396a-8d16-4239-8bc6-8323e58437bd)


And, This is the simulation
![simulation](https://github.com/MAliKaya53/SPI_Slave/assets/83914338/523fd3fe-e8e0-4f37-8ffc-b8cc9e41f7f6)

