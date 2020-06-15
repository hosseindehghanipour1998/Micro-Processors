In this project 2 slaves are connected to a master microcontroller
master uses addresses to handle data transmission to both microcontrollers (same RX data line for both slaves)
One slave does not have Transmission wire , because if both TX pins of both slaves are connected to RX of Master
logic contention occures , since only one slave sends data to Master (as in Project only Slave 1 does) we dont need
to handle this , if it was needed we could use a multiplexer and different TX buses for Slaves.