Download Link: https://assignmentchef.com/product/solved-csci2500-lab-8-imulation-of-logical
<br>
<ol>

 <li><strong>: </strong>For the first (and second) checkpoint, you will use C to finish implementing a simulation of logical NOT, logical OR, logical AND, and logical XOR.</li>

</ol>

Download the lab08.c code, which provides fill-in-the-blank skeletal code for these logical gates, as well as unit test code in main(). Fill in the not_gate(), or_gate(), and_gate(), and xor_gate() functions. Verify that the truth table outputs are correct.

<ol start="2">

 <li><strong>Checkpoint 2: </strong>For the second checkpoint, continue to add to the c code by implementing the multiplexer(), decoder(), and sr_latch() functions. Also add code to main() to comprehensively test your decoder() and sr_latch() functions. As above, verify that the truth table outputs are correct.</li>

 <li><strong>Checkpoint 3: </strong>For the third checkpoint, write a function called ieee754encode() that has the function prototype shown below and generates the encoding of a single-precision floating-point value in its 32-bit binary form.</li>

</ol>

void ieee754encode( float value, char * encoded );

This function accepts two arguments. The value argument is the actual single-precision floating-point value to be encoded (e.g., 57.75). The encoded argument points to where the normalized binary string should be stored, with the binary string representing the IEEE 7541985 form (e.g., “01000010011001110000000000000000”).

You can assume that the encoded argument points to a valid chunk of memory of at least 33 bytes. And as a character string, you will need to generate the correct series of ‘0’ and ‘1’ characters. <strong>Be sure to use the normalized form.</strong>

Your function should output the following debugging information:

input: 57.750000 sign: 0 exponent: 10000100 fraction: 11001110000000000000000 output: 01000010011001110000000000000000