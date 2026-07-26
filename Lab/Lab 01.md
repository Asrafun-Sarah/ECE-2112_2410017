## **Lab 1: Introduction of Basic Gates **
## **Task 1: Implementation of OR Gate using NOR Gates**

**Introduction:**\
In this experiment, an OR gate will be constructed using only NOR gates. An OR gate produces a HIGH output (1) if at least one of its inputs is HIGH (1). Since the NOR gate is a universal logic gate, it can be used to implement other basic logic gates, including the OR gate.

**Procedure:**
1. **Study of the NOR Gate:**
   - A NOR gate is formed by combining an OR gate with a NOT gate. Its output is HIGH (1) only when all of its inputs are LOW (0).
   - The truth table of a 2-input NOR gate is given below:

   | Input A | Input B | Output (A NOR B) |
   |---------|---------|------------------|
   |    0    |    0    |         1        |
   |    0    |    1    |         0        |
   |    1    |    0    |         0        |
   |    1    |    1    |         0        |

2. **Construction of an OR Gate Using NOR Gates:**
   - To implement an OR gate using NOR gates, we can use the following logic:
   - The OR gate can be expressed in terms of NOR gates as follows:
   - OR(A, B) = NOT(NOR(A, B))
   - This means that we can first use a NOR gate to get the output of NOR(A , B), and then use another NOR gate to invert that output.  

3. **Circuit Design:**
   - Connect the inputs A and B to the first NOR gate.
     
   <img width="453" height="306" alt="Screenshot 2026-07-26 at 6 03 56 AM" src="https://github.com/user-attachments/assets/4ece9f54-e515-4bb8-85ef-0d3824a5b914" />
   
   - Connect the output of the first NOR gate to both inputs of the second NOR gate to invert the output.
     
   <img width="681" height="321" alt="Screenshot 2026-07-26 at 6 04 27 AM" src="https://github.com/user-attachments/assets/e7810cbf-b2c5-41be-a158-82243cf64b42" />


4. **Testing the Circuit:**
   - Apply different combinations of inputs (A and B) to the circuit and observe the output.
   - Verify that the output matches the expected results of an OR gate.
   
   <img width="633" height="241" alt="Screenshot 2026-07-26 at 6 04 57 AM" src="https://github.com/user-attachments/assets/1c8212ea-3df1-4fe8-8466-fe7e978fcb30" />


   <img width="650" height="239" alt="Screenshot 2026-07-26 at 6 05 18 AM" src="https://github.com/user-attachments/assets/1cbd7879-a448-45df-aa88-f22f5171d041" />


**Conclusion:**
In this experiment, an OR gate was successfully constructed using only NOR gates. The experiment demonstrated that NOR gates, being universal gates, can be used to implement other basic logic gates. This experiment helped reinforce the concept of universal gates and their importance in digital logic circuit design.

## **Task 2: Implementation of an OR Gate using NAND Gates**

**Introduction::**\
In this experiment, an OR gate is constructed using only NAND gates. NAND is a universal logic gate, meaning that it can be used to implement all other basic logic gates, including the OR gate.

**Procedure:**
1. **Study of the NAND Gate:**
   -A NAND gate is formed by combining an AND gate with a NOT gate. Its output is LOW (0) only when all of its inputs are HIGH (1).
   - The truth table for a 2-input NAND gate is as follows:
   
   | Input A | Input B | Output (A NAND B) |
   |---------|---------|-------------------|
   |    0    |    0    |        1          |
   |    0    |    1    |        1          |
   |    1    |    0    |        1          |
   |    1    |    1    |        0          |

2. **Implementing the OR Gate using NAND Gates:**
   - To implement an OR gate using NAND gates, we can use the following logic:
   - OR(A, B) = NOT(NAND(NOT(A), NOT(B)))
   - This means that we can first use two NAND gates to invert the inputs A and B, and then use a third NAND gate to combine the inverted inputs.
3. **Circuit Design:**
   - Connect the inputs A and B to the first two NAND gates to invert them.
   - Connect the outputs of the first two NAND gates to the inputs of the third NAND gate to get the final output.
<img width="625" height="317" alt="Screenshot 2026-07-26 at 6 13 32 AM" src="https://github.com/user-attachments/assets/0bcde91b-e9ef-4931-87cc-44e041b62ab8" />


4. **Testing the Circuit:**
   - Apply different combinations of inputs (A and B) to the circuit and observe the output.
   - Verify that the output matches the expected results of an OR gate.

   <img width="612" height="322" alt="Screenshot 2026-07-26 at 6 14 05 AM" src="https://github.com/user-attachments/assets/40eaee9e-2249-4717-9872-ddda5a8b2d1a" />
   
   <img width="607" height="319" alt="Screenshot 2026-07-26 at 6 14 48 AM" src="https://github.com/user-attachments/assets/455252fd-ecb4-4adc-bafa-54785181468e" />



**Conclusion:**
   In this experiment, an OR gate was successfully implemented using three NAND gates. The experiment demonstrated the practical application of De Morgan's theorem and verified that NAND gates can be used to construct other logic gates. This experiment also strengthened the understanding of universal gates and their significance in digital logic circuit design.

## **Task 3: Implementation of AND Gate using NOR Gates**

**Introduction:**\
In this experiment, an AND gate is constructed using only NOR gates. An AND gate produces a HIGH output (1) only when both of its inputs are HIGH (1). Since NOR is a universal logic gate, it can be used to implement an AND gate.

**Procedure:**
1. **Study of the AND Gate:**
   - An AND gate outputs true (1) only when both of its inputs are true (1). The truth table for a 2-input AND gate is as follows:

   | Input A | Input B | Output (A AND B) |
   |---------|---------|-------------------|
   |    0    |    0    |        0          |
   |    0    |    1    |        0          |
   |    1    |    0    |        0          |
   |    1    |    1    |        1          |

2. **Implementing the AND Gate using NOR Gates:**
   - To implement an AND gate using NOR gates, we can use the following logic:
   - AND(A, B) = NOT(NOR(NOT(A), NOT(B)))
   - This means that we can first use two NOR gates to invert the inputs A and B, and then use a third NOR gate to combine the inverted inputs.

3. **Circuit Design:**
   - Connect the inputs A and B to the first two NOR gates to invert them.
   - Connect the outputs of the first two NOR gates to the inputs of the third NOR gate to get the final output.

    <img width="597" height="276" alt="Screenshot 2026-07-26 at 6 20 43 AM" src="https://github.com/user-attachments/assets/ffbcc180-da0c-4102-8456-191c51763886" />


4. **Testing the Circuit:**
   - Apply different combinations of inputs (A and B) to the circuit and observe the output.
   - Verify that the output matches the expected results of an AND gate.

<img width="586" height="320" alt="Screenshot 2026-07-26 at 6 21 16 AM" src="https://github.com/user-attachments/assets/bc7f25e3-24b4-42c9-ad97-ffa81aeb3a18" />

<img width="615" height="322" alt="Screenshot 2026-07-26 at 6 21 46 AM" src="https://github.com/user-attachments/assets/7ee9bde3-debc-4966-b6af-fd3b435e3973" />



**Conclusion:**
In this experiment, an AND gate was successfully implemented using three NOR gates. The experiment demonstrated how a universal gate can be used to construct other basic logic gates. It also provided a practical understanding of De Morgan's theorem and the importance of universal gates in digital logic circuit design.

## **Experiment 4: Implementation of AND Gate using NAND Gates**

**Introduction:**\
In this experiment, an AND gate is constructed using only NAND gates. Since NAND is a universal logic gate, it can be used to implement various other logic gates, including the AND gate.

**Procedure:**
1. **Study of the AND Gate:**
   - An AND gate outputs true (1) only when both of its inputs are true (1). The truth table for a 2-input AND gate is as follows:

    | Input A | Input B | Output (A AND B) |
    |---------|---------|-------------------|
    |    0    |    0    |        0          |
    |    0    |    1    |        0          |
    |    1    |    0    |        0          |
    |    1    |    1    |        1          |


2. **Implementing the AND Gate using NAND Gates:**
   - To implement an AND gate using NAND gates, we can use the following logic:
   - AND(A, B) = NOT(NAND(A, B))
   - This means that we can first use a NAND gate to get the output of NAND(A, B), and then use another NAND gate to invert that output.

3. **Circuit Design:**
   - Connect the inputs A and B to the first NAND gate.
   - Connect the output of the first NAND gate to both inputs of the second NAND gate to invert the output.
  
   <img width="596" height="214" alt="Screenshot 2026-07-26 at 6 25 48 AM" src="https://github.com/user-attachments/assets/2612cb4b-732d-484f-b4fe-5d9b8792a349" />


4. **Testing the Circuit:**
   - Apply different combinations of inputs (A and B) to the circuit and observe the output.
   - Verify that the output matches the expected results of an AND gate.

   <img width="569" height="215" alt="Screenshot 2026-07-26 at 6 26 14 AM" src="https://github.com/user-attachments/assets/c1af9f5c-a6b6-466b-875b-f8213e77d348" />
   <img width="591" height="281" alt="Screenshot 2026-07-26 at 6 26 37 AM" src="https://github.com/user-attachments/assets/b3c5f94a-bc74-490f-afd8-84938f97c207" />


**Conclusion:**
In this experiment, an AND gate was successfully implemented using two NAND gates. The experiment demonstrated how a NAND gate can be used to construct an AND gate by performing an additional inversion. This experiment also reinforced the concept of universal gates and their practical application in digital logic circuit design.

## **Task 5: Implementation of NOT Gate using NOR Gates**


**Introduction:**\
In this experiment, a NOT gate is implemented using only a NOR gate. A NOT gate, also known as an inverter, produces the complement of its input value. Since a NOR gate is a universal gate, it can be used to construct a NOT gate by connecting its inputs together.

**Procedure:**
1. **Study of the NOT Gate:**
   - A NOT gate outputs true (1) when its input is false (0) and outputs false (0) when its input is true (1). The truth table for a NOT gate is as follows:

   | Input A | Output (NOT A) |
   |---------|----------------|
   |    0    |        1       |
   |    1    |        0       |

2. **Implementing the NOT Gate using NOR Gates:**
   - To implement a NOT gate using NOR gates, we can use the following logic:
   - NOT(A) = NOR(A, A)
   - This means that we can connect the input A to both inputs of a NOR gate to get the inverted output.


3. **Circuit Design:**
   - Connect the input A to both inputs of the NOR gate.

  <img width="364" height="184" alt="Screenshot 2026-07-26 at 6 31 45 AM" src="https://github.com/user-attachments/assets/e7f46649-317c-4293-ae40-1aeaf1eba7c7" />

4. **Testing the Circuit:**
   - Apply different values of input A to the circuit and observe the output.
   - Verify that the output matches the expected results of a NOT gate.

   <img width="368" height="181" alt="Screenshot 2026-07-26 at 6 32 28 AM" src="https://github.com/user-attachments/assets/f63e5002-3462-4b76-aec1-0d0e7729d29a" />
   <img width="386" height="183" alt="Screenshot 2026-07-26 at 6 32 42 AM" src="https://github.com/user-attachments/assets/e38ef61f-aac8-43fd-9fce-ffd5adaf3447" />


**Conclusion:**
In this experiment, a NOT gate was successfully implemented using a single NOR gate. The experiment demonstrated that NOR gates can be used to construct other basic logic gates due to their universal nature. This helped strengthen the understanding of universal gates and their importance in digital logic circuit design.


## **Task 6: Implementation of NOT Gate using NAND Gates**

**Description:**\
In this experiment, we will implement a NOT gate using only NAND gates. The NOT gate is a fundamental digital logic gate that outputs the opposite value of its input. The NAND gate, being a universal gate, can be used to create a NOT gate as well.

**Procedure:**
1. **Understanding the NOT Gate:**
   - A NOT gate outputs true (1) when its input is false (0) and outputs false (0) when its input is true (1). The truth table for a NOT gate is as follows:

   | Input A | Output (NOT A) |
   |---------|----------------|
   |    0    |        1       |
   |    1    |        0       |

2. **Implementing the NOT Gate using NAND Gates:**
   - To implement a NOT gate using NAND gates, we can use the following logic:
   - NOT(A) = NAND(A, A)
   - This means that we can connect the input A to both inputs of a NAND gate to get the inverted output.

3. **Circuit Design:**
   - Connect the input A to both inputs of the NAND gate.
     
<img width="358" height="204" alt="Screenshot 2026-07-26 at 6 39 03 AM" src="https://github.com/user-attachments/assets/72d22792-3709-4202-b1de-1801ffde30f9" />


4. **Testing the Circuit:**
   - Apply different values of input A to the circuit and observe the output.
   - Verify that the output matches the expected results of a NOT gate.

  <img width="361" height="166" alt="Screenshot 2026-07-26 at 6 39 35 AM" src="https://github.com/user-attachments/assets/2b0ebf70-a6c1-432c-be84-15b2c7dbbe62" />
<img width="385" height="173" alt="Screenshot 2026-07-26 at 6 39 51 AM" src="https://github.com/user-attachments/assets/011535e8-6f9e-469f-b4db-7215a64547bb" />


**Conclusion:**
In this experiment, a NOT gate was successfully implemented using a single NOR gate. The experiment demonstrated that NOR gates can be used to construct other basic logic gates due to their universal nature. This helped strengthen the understanding of universal gates and their importance in digital logic circuit design.


## **Experiment 7: Implementation of Full Adder and testing it.**

**Description:**\
In this experiment, we will implement a Full Adder circuit using basic logic gates. A Full Adder is a digital circuit that performs the addition of three binary bits: two significant bits and a carry bit. The Full Adder produces a sum and a carry output.

**Procedure:**
1. **Study of the Full Adder:**
   - A Full Adder takes three inputs: A, B, and Cin (carry input). It produces two outputs: Sum and Cout (carry output). The truth table for a Full Adder is as follows:

   | Input A | Input B | Cin | Sum | Cout |
   |---------|---------|-----|-----|------|
   |    0    |    0    |  0  |  0  |  0   |
   |    0    |    0    |  1  |  1  |  0   |
   |    0    |    1    |  0  |  1  |  0   |
   |    0    |    1    |  1  |  0  |  1   |
   |    1    |    0    |  0  |  1  |  0   |
   |    1    |    0    |  1  |  0  |  1   |
   |    1    |    1    |  0  |  0  |  1   |
   |    1    |    1    |  1  |  1  |  1   |

2. **Implementing the Full Adder Circuit:**
   - The Full Adder can be implemented using two Half Adders and an OR gate.
   - The first Half Adder takes inputs A and B and produces a sum (S1) and a carry (C1).
   - The second Half Adder takes the sum (S1) from the first Half Adder and the carry input (Cin) to produce the final sum (Sum) and a carry (C2).
   - The final carry output (Cout) is obtained by ORing the two carry outputs (C1 and C2) from the two Half Adders.

3. **Circuit Design:**
   - Connect the inputs A and B to the first Half Adder.
   ![alt text](image-20.png)
   - Connect the sum output (S1) from the first Half Adder and the carry input (Cin) to the second Half Adder.
   ![alt text](image-21.png)
   - Connect the carry outputs (C1 and C2) from both Half Adders to an OR gate to produce the final carry output (Cout).
   ![alt text](image-22.png)

4. **Testing the Circuit:**
   - Apply different combinations of inputs (A, B, and Cin) to the circuit and observe the outputs (Sum and Cout).
   - Verify that the outputs match the expected results of a Full Adder.
   ![alt text](image-23.png)
   ![alt text](image-24.png)
   ![alt text](image-25.png)
   For 8 bit the main full adder shows 10 in s and 0 in carry out. If we think about 1 bit the sum is 0 and carry out is 1 which is correct according to the circuit we have designed.
   ![alt text](image-26.png)
   Same as before for 8 bit the main full adder shows 11 in s and 0 in carry out. If we think about 1 bit the sum is 1 and carry out is 1 which is correct according to the circuit we have designed.

**Conclusion:**
In this experiment, we successfully implemented a Full Adder circuit using basic logic gates. By understanding the properties of Half Adders and their combination to form a Full Adder, we were able to demonstrate the addition of binary numbers. This exercise reinforces the concept of digital arithmetic and its applications in digital circuits. The Full Adder is a crucial component in the design of arithmetic logic units (ALUs) and other digital systems that require binary addition.


## **Experiment 8: Implementation of Binary to BCD Converter**

**Description:**\
In this experiment, a Binary-to-BCD converter is implemented using logic gates. The purpose of the circuit is to convert a 4-bit binary number into its equivalent Binary-Coded Decimal (BCD) representation. In BCD, each decimal digit is represented separately using a 4-bit binary code.

**Procedure:**
1. **Study of Binary to BCD Conversion:**
   - A Binary to BCD converter takes a binary input and produces a BCD output.
   - For example, the binary number 1010 (which is 10 in decimal) can be represented in BCD as 0001 0000 (1 and 0 in BCD).
   - The truth table for a 4-bit binary input and its corresponding BCD output is as follows:

| Binary Code |   |   |   | BCD Code |   |   |   |
|:-----------:|:-:|:-:|:-:|:--------:|:-:|:-:|:-:|
| B₃ | B₂ | B₁ | B₀ | D₄ | D₃ | D₂ | D₁ |
| 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| 0 | 0 | 0 | 1 | 0 | 0 | 0 | 1 |
| 0 | 0 | 1 | 0 | 0 | 0 | 1 | 0 |
| 0 | 0 | 1 | 1 | 0 | 0 | 1 | 1 |
| 0 | 1 | 0 | 0 | 0 | 1 | 0 | 0 |
| 0 | 1 | 0 | 1 | 0 | 1 | 0 | 1 |
| 0 | 1 | 1 | 0 | 0 | 1 | 1 | 0 |
| 0 | 1 | 1 | 1 | 0 | 1 | 1 | 1 |
| 1 | 0 | 0 | 0 | 1 | 0 | 0 | 0 |
| 1 | 0 | 0 | 1 | 1 | 0 | 0 | 1 |
| 1 | 0 | 1 | 0 | 1 | 0 | 1 | 0 |
| 1 | 0 | 1 | 1 | 1 | 0 | 1 | 1 |
| 1 | 1 | 0 | 0 | 1 | 1 | 0 | 0 |
| 1 | 1 | 0 | 1 | 1 | 1 | 0 | 1 |
| 1 | 1 | 1 | 0 | 1 | 1 | 1 | 0 |
| 1 | 1 | 1 | 1 | 1 | 1 | 1 | 1 |

2. **Implementing the Binary to BCD Converter Circuit:**
   - The Binary to BCD converter can be implemented using a combination of logic gates to map the binary inputs to their corresponding BCD outputs.
   - The circuit design will involve creating logic expressions for each BCD output bit (D₄, D₃, D₂, D₁) which will be displayed on the BCD to seven-segment display based on the binary input bits (B₃, B₂, B₁, B₀).

3. **Circuit Design:**
   - Connect the binary input bits (B₃, B₂, B₁, B₀) to the Binary to BCD converter circuit.
   - The circuit will produce the corresponding BCD output bits (D₄, D₃, D₂, D₁) based on the input binary number which will be displayed on the BCD to seven-segment display.
   - 
<img width="633" height="347" alt="Screenshot 2026-07-26 at 6 46 48 AM" src="https://github.com/user-attachments/assets/df6ed3b4-3890-4235-ab0f-8778d0bcc257" />

   
4. **Testing the Circuit:**
   - Apply different combinations of binary inputs (B₃, B₂, B₁, B₀) to the circuit and observe the BCD outputs (D₄, D₃, D₂, D₁).
   - Verify that the outputs match the expected results of the Binary to BCD conversion.
   <img width="619" height="392" alt="Screenshot 2026-07-26 at 6 47 32 AM" src="https://github.com/user-attachments/assets/2f9a5920-8b0e-4d4d-86b6-d52de55905dd" />
   
<img width="639" height="378" alt="Screenshot 2026-07-26 at 6 48 01 AM" src="https://github.com/user-attachments/assets/a89cbb85-9e66-477e-88cd-51af12afeba5" />


**Conclusion:**
In this experiment, a Binary-to-BCD converter was successfully implemented and tested. The circuit converted 4-bit binary numbers into their corresponding BCD representations, allowing the binary values to be displayed as decimal digits. This experiment provided a practical understanding of binary-to-BCD conversion and demonstrated its importance in digital systems such as digital displays, calculators, and other electronic devices that require decimal number representation.


## <h1 align='center'>  End of Lab 1 Report  </h1>
