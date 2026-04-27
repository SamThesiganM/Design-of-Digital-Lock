# Digital Lock

Digital Lock is a foundational element of modern security, ranging from complex
cryptographic systems used in financial transactions to simple electronic locks for
restricted areas. The fundamental requirement in all these systems is the robust and
accurate verification of an input sequence against a known, stored pattern.

## Project Description

This mini-project focuses on designing a basic, yet illustrative, sequential circuit capable of
performing this task for a three-digit password. The challenge lies in sequentially
validating each incoming digit while ensuring that the input order is maintained, which
requires incorporating sequential logic to manage the state of the verification process.

## Components Used

- Encoder  
- MOD-4 Counter  
- 2:4 Decoder  
- Digital Comparators  
- D Flip-Flops  

## Working

1. The user enters digits through a keypad.
2. The **Encoder** converts each key press into binary form.
3. The **MOD-4 Counter** keeps track of the position (1st, 2nd, 3rd digit).
4. Based on the counter output, the **2:4 Decoder** selects the corresponding stored password digit.
5. The entered digit is compared with the stored digit using **Digital Comparators**.
6. The result of each comparison is stored using **D Flip-Flops**.
7. After all three digits are entered:
   - If all comparisons are correct → Access is **granted** 
   - If any digit is incorrect → Access is **denied**  

## Conclusion

This combination ensures that the system not only checks for data equality but also confirms that the key
presses occur in the correct, predetermined order. The successful implementation of this
circuit serves as a practical demonstration of integrating combinational and sequential logic
for real-world security applications.
