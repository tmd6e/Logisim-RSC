Logisim can be installed through this link: https://sourceforge.net/projects/circuit/files/2.7.x/2.7.1/logisim-win-2.7.1.exe/download

When testing the RSC's assembly programs, follow these instructions:
1. Open RSC.circ in Logisim.
2. Navigate to the RSC circuit under the RSC project folder.
3. Find and right-click the RAM component in the upper-right area of the circuit.
4. Select Load Image and choose any one of the bytecode text files under the Programs folder.
5. Navigate to Simulate at the top of the window and ensure Simulation Enabled is on.
6. In the Simulate dropdown menu, set the tick frequency to 4.1 KHz (or any desired frequency) and toggle on Ticks Enabled.
NOTE: Before testing another bytecode file, select Simulate >> Reset Simulation and toggle off Ticks Enabled. After that, repeat Steps 3 through 6 with the desired bytecode.

Program 1: Subtracts the binary number 0xA from 0xF.
Program 2: Performs addition, subtraction, logical AND/OR/NOT, right shift, and increment on binary numbers 0xA9 and 0x2B.
Program 3: Reverses the bits of a given binary number.
