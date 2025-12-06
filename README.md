# SERIAL-IN-SERIAL-OUT-SHIFTREGISTER

**AIM:**

To implement  SISO Shift Register using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

**SISO shift Register**

A Serial-In Serial-Out shift register is a sequential logic circuit that allows data to be shifted in and out one bit at a time in a serial manner. It consists of a cascade of flip-flops connected in series, forming a chain. The input data is applied to the first flip-flop in the chain, and as the clock pulses, the data propagates through the flip-flops, ultimately appearing at the output.

The logic circuit provided below demonstrates a serial-in serial-out (SISO) shift register. It comprises four D flip-flops that are interconnected in a sequential manner. These flip-flops operate synchronously with one another, as they all receive the same clock signal.

![image](https://github.com/naavaneetha/SERIAL-IN-SERIAL-OUT-SHIFTREGISTER/assets/154305477/e81c4072-37f9-46c6-8145-566764b74c3a)

Figure 01 4 Bit SISO Register

The synchronous nature of the flip-flops ensures that the shifting of data occurs in a coordinated manner. When the clock signal rises, the input data is sampled and stored in the first flip-flop. On subsequent clock pulses, the stored data propagates through the flip-flops, moving from one flip-flop to the next.
Each D flip-flop in the circuit has a Data (D) input, a Clock (CLK) input, and an output (Q). The D input represents the data to be loaded into the flip-flop, while the CLK input is connected to the common clock signal. The output (Q) of each flip-flop is connected to the D input of the next flip-flop, forming a cascade.

**Procedure**

1).Compile and run the program.

2).Generate the RTL schematic and save the logic diagram.

3).Create nodes for inputs and outputs to generate the timing diagram.

4).For different input combinations generate the timing diagram.


**PROGRAM**

![WhatsApp Image 2025-12-06 at 21 25 06_060ecbc6](https://github.com/user-attachments/assets/7a3df9de-105f-438c-aa79-4683f5aab982)


Developed by:PIRUTHIVIRAJ G RegisterNumber:25016420



**RTL LOGIC FOR SISO Shift Register**

![WhatsApp Image 2025-12-06 at 21 25 06_8707c64f](https://github.com/user-attachments/assets/df5e6c97-bfed-4c55-b7ac-9ebf1d60fa7e)

**TIMING DIGRAMS FOR SISO Shift Register**

![WhatsApp Image 2025-12-06 at 21 25 06_8dffcacc](https://github.com/user-attachments/assets/d4ab426f-7b47-4fb9-a9bb-16072a2f1b92)

**RESULTS**

SISO Shift Register using verilog and validating their functionality using their functional tables has successful execution of the program.
