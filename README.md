CRC-Cyclic Redundancy Check
===
This is basically a error detection algorithm generally used in Computer Networks.
In this algorithm ,It checks the stream of binary bits and as of whatever length length we have to generate the CRC we can generate with help of CRC generator.
The data stream of bits are appended with the (length of CRC generator-1)[E] 0 at end and try to divide data with CRC generator and whatever is the  remainder (length of CRC generator-1) from LSB are been taken and replaced with that appended 0
and then data is been sent
At receiver side also the that recived data is been divide with CRC generator and if remainder is 0 thendata is correct else It has been corrupted.
