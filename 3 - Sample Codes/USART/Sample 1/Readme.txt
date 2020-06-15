in this example , both receiver and transmitter use the same code :
sending "hellooo" to the other microcontroller , character by character
receiving the character
as INT for reciever is enabled : 
1- lcd_putchar(data); , data is UDR value when data is received
2- use rx_rw_index to see how many characters received

-> read C code for Receive ISR and change code to see the difference