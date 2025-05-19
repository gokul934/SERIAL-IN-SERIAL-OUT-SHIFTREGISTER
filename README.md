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

1. Intialize the shift register to know state(e.g., all zeros).
2. Input a bit serially into the shift register.
3. shift the content of the register one position to the right (or left).
4. output the shifted bit from the last stage of the register.
5. Repeat steps 2-4 for each bit you want to input and shift.

**PROGRAM**

![image](https://github.com/user-attachments/assets/541f1959-539e-418d-a00e-fae591be6ddd)


**RTL LOGIC FOR SISO Shift Register**

![image](https://github.com/user-attachments/assets/3e184ab7-ac76-4205-ae9e-9da14df51b70)


**TIMING DIGRAMS FOR SISO Shift Register**

![image](https://github.com/user-attachments/assets/4e92158c-edc4-43d5-b053-36f67d53a559)


**RESULTS**

Thus implemented SISO shift register using verilog and validated their functionality using their functional tables.
