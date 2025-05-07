This package includes the source code main.cpp to implement binary overlapped arithmetic codes for nonuniformly distributed sources. At the top of main.cpp there are three macro definitions:
#define LED
#define LAST
#define CCS

If the macro CCS is uncommented, coset cardinality spectrum (CCS) will be used during decoding and a better performance can be achieved. (This is well known in my previous papers)
If the macro LAST is uncommented, the last symbol of each block will be specifically encoded and decoded, and a better performance can be achieved. (This is new!)
If the macro LED is uncommented, the local encoder at decoder structure will be used, and a better performance can be achieved. (This is new!)

This job was supported by the National Science Foundation of China under grant 62350069.

