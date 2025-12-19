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

/* write all the steps invloved */
All D flip-flops in the circuit are connected to a common clock (CLK), ensuring synchronous operation.

Each D flip-flop has:

D (Data) input – to receive the data,

CLK (Clock) input – to control when data is stored,

Q output – which holds the stored data.

The Q output of each flip-flop is connected to the D input of the next flip-flop, forming a cascade (shift register structure).

When the clock signal rises (active clock edge):

The input data is sampled and stored in the first flip-flop.

On each subsequent clock pulse:

The data stored in one flip-flop is transferred to the next flip-flop in the sequence.

Thus, the data shifts from one stage to the next in a coordinated manner.

Because all flip-flops operate on the same clock edge, data shifting occurs simultaneously and synchronously throughout the circuit.

**PROGRAM**

/* Program for flipflops and verify its truth table in quartus using Verilog programming.

Developed by:G.Muthu Manikkam RegisterNumber:25016274

*/
<img width="465" height="383" alt="Screenshot 2025-12-19 180406" src="https://github.com/user-attachments/assets/b742e6a5-a547-48e7-8497-a711ddea4196" />


**RTL LOGIC FOR SISO Shift Register**
<img width="1307" height="903" alt="exp10(RTL Program)" src="https://github.com/user-attachments/assets/d7edef83-f093-4f9c-925f-b9247ce5980b" />


**TIMING DIGRAMS FOR SISO Shift Register**
<img width="1919" height="1014" alt="Screenshot 2025-12-19 181432" src="https://github.com/user-attachments/assets/6c5f08a6-76f2-494f-9071-a1189cc662de" />

**RESULTS**
 Thus the Serial-In Serial-Out shift register is implemented and verified.
