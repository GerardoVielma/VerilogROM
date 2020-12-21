# VerilogROM
Program Description: Verilog Module is ROM, it holds 32 unsigned intergers each 8 bits which requires 5 address lines(A [4:0]).
                     The LED [15:11] displays the address lines that are set by lighting up.
                     It has a parallel Load function using the 8 bit slide switches 7:0 and latches data to ROM when
                     the left button is pressed. Right button "Clears" zeros 1 byte that is addressed.
                     LED [7:0] displays the value stored in the ROM at the addressed location. 
