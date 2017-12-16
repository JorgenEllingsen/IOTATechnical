# The Trinary Numbers System

## Little endian numbers
The difference between little and big endian numbers is the Most Significant Bit (MSB) position. It is easy to remeber as Big-end first and Little-end first, so Big endian numbers start with MSB and Little endian starts with Least Significant Bit (LBS).

## Balanced Trinary Number System
The trinary number system can either be used balanced, or unbalanced. The balanced trinary system works with the three values -1, 0, or 1, while the balanced trinary system uses the values 0, 1 and 2 - both called a trit.
IOTA is using the unbalanced trinary system for the system to be efficiently implemented in hardware. Balanced trinary can be represented as positive current, no current or negative current, and will be well suited for special purpose processors in the future.

## Trinary Number System in IOTA
The seeds in IOTA can contain A-Z and 9, giving 27 different characters. A trite (Trinary "Byte") is three trits (Trinary "Bits"), and each character in a seed represents three trists - 3^3, 27 values.



### References 
https://www.cs.umd.edu/class/sum2003/cmsc311/Notes/Data/endian.html
https://iota.stackexchange.com/questions/742/trinary-numeral-system-and-lamport-signature
https://www.youtube.com/watch?v=2pBZJvVn4NY
