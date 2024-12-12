### ENCODER 8TO3 DATAFLOW Modelling

**AIM:**

To implement  Encoder 8 To 3 in Dataflow Modelling using verilog and validating their functionality using their functional tables

**SOFTWARE REQUIRED:** Quartus prime

**THEORY**

**Encoder 8 To 3**

The 8 to 3 line Encoder is also known as Octal to Binary Encoder. In 8 to 3 line encoder, there is a total of eight inputs, i.e., D0, D1, D2, D3, D4, D5, D6, and D7 and three outputs, i.e., A0, A1, and A2. In 8-input lines, one input-line is set to true at a time to get the respective binary code in the output side. Below are the block diagram and the truth table of the 8 to 3 line encoder.

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/0bc242c1-eb9e-4c47-afe5-30428470efc3)

Figure 01  Block Diagram of Encoder 8 * 3

**Truth Table**

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/35496b14-ae6e-4cd1-9abd-d6736b576575)

The logical expression of the term A0, A1, and A2 are as follows:

A0 = D1 + D3 + D5 + D7

A1 = D2 + D3 + D6 + D7

A2 = D4 + D5 + D6 + D7

Logical circuit of the above expressions is given below:

![image](https://github.com/naavaneetha/ENCODER8TO3DATAFLOW/assets/154305477/95acaee6-c873-4c75-89eb-ef09fb158053)

Figure 02  Encoder 8 * 3

**Procedure**
/*1.Type the program in Quartus software. 2.compile and run the program. 3.generate the RTL schematic and save the logic diagram. 4.create nodes for inputs and outputs to generate the timing diagram. 5.for different input combinations generate the timing diagram.*/

/* write all the steps invloved */

**PROGRAM**

/* Program for Encoder 8 To 3 in Dataflow Modelling and verify its truth table in quartus using Verilog programming. 

Developed by:MAGENDRA SANJAY S RegisterNumber:24900652






![WhatsApp Image 2024-12-11 at 10 05 33](https://github.com/user-attachments/assets/df58d384-7586-4ebc-bec7-9a994732d360)






**RTL LOGIC FOR Encoder 8 To 3 in Dataflow Modelling**










![WhatsApp Image 2024-12-11 at 10 05 47](https://github.com/user-attachments/assets/d05c9264-8118-4f54-8ca9-384ee3fbe708)







**TIMING DIGRAMS FOR Encoder 8 To 3 in Dataflow Modelling**









![WhatsApp Image 2024-12-11 at 10 06 04](https://github.com/user-attachments/assets/d4f97458-26f9-40d9-ad97-4f8904efbc5b)










**RESULTS**

Thus the ENCODER 8 TO 3 is designed and the truth table is verified


