# Evolve-I2C-PIC16
We are using a PIC16F1783 to control relays, EC fans and triacs, and read those RHT/DHT sensors, and we still want to use the SBC66EC as the ‘Brains’ of the system. The PIC16F1783 will be the slave.
But right now we are a bit suck on establishing communication between the SBC and our PIC16. We would like the SBC to talk to the PIC16 the same way it does with your relay boards. And we would also like to be able to send temperature/humidity strings back to the SBC from the PIC16 slave. 

The Master sending strings to the slave is the important part we would like to have first. The slave sending strings to the master is not urgent and I might be able to figure it out later.
We are trying to use RB6 and RB7 on the PIC16 for the I2C.
