**SR-FLIPFLOP-USING-CASE**

**AIM:**

To implement SR flipflop using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:**

Quartus prime

**THEORY**

SR Flip-Flop SR flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, SR latch operates with enable signal. The circuit diagram of SR flip-flop is shown in the following figure.

![alt text](<SR Flip Flop Gates.png>)

This circuit has two inputs S & R and two outputs Qtt & Qtt’. The operation of SR flipflop is similar to SR Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of SR flip-flop.

![alt text](<SR Flip Flop Tables.png>)

Here, Qtt & Qt+1t+1 are present state & next state respectively. So, SR flip-flop can be used for one of these three functions such as Hold, Reset & Set based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of SR flip-flop. Present Inputs Present State Next State

![alt text](<SR Flip Flop Table 2.png>)

By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. The three variable K-Map for next state, Qt+1t+1 is shown in the following figure.

![alt text](<Screenshot 2025-12-09 113548.png>)

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=S+R′Q(t)Q(t+1)=S+R′Q(t)

**Procedure**
1. Type the program in Quartus software.
2. Compile and run the program.
3. Generate the RTL schematic and save the logic diagram.
4. Create nodes for inputs and outputs to generate the timing diagram.
5. For different input combinations generate the timing diagram

**PROGRAM**

![alt text](<SR Flip Flop Program.png>)


Developed by: Sandya S         RegisterNumber: 25017264

**RTL LOGIC FOR FLIPFLOPS**

![alt text](<RTL Logic of SR Flip Flop.png>)

**TIMING DIGRAMS FOR FLIP FLOPS**

![alt text](<SR Flip Flop wave.png>)

**RESULTS**
Thus, the SR Flip Flop is designed and the truth tables is verified using Quartus software.

.....


.....










.....








.....







.....







.....









......









......












.....











.....











.....










....








.....







....



















...
