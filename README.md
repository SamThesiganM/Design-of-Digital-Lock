#!/bin/bash

para="Digital access control is a foundational element of modern security, ranging from complex
cryptographic systems used in financial transactions to simple electronic locks for
restricted areas. The fundamental requirement in all these systems is the robust and
accurate verification of an input sequence against a known, stored pattern.
This mini-project focuses on designing a basic, yet illustrative, sequential circuit capable of
performing this task for a three-digit password. The challenge lies in sequentially
validating each incoming digit while ensuring that the input order is maintained, which
requires incorporating sequential logic to manage the state of the verification process.
The proposed solution integrates several core digital components: an Encoder to translate
physical keypad input into binary data, a MOD-4 Counter to track the position in the
sequence, a 2:4 Decoder to select the corresponding stored digit for comparison, a series of
Digital Comparators and 3-D flip flops to store the comparator outputs. This combination
ensures that the system not only checks for data equality but also confirms that the key
presses occur in the correct, predetermined order. The successful implementation of this
circuit serves as a practical demonstration of integrating combinational and sequential logic
for real-world security applications."

echo "----------------------------------------"
echo "        MINI PROJECT DESCRIPTION"
echo "----------------------------------------"
echo "$para"
echo "----------------------------------------"
