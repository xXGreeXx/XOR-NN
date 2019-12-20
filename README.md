# XOR-NN

Simple neural network trained on an XOR table, written entirely in Brainfuck ( https://en.wikipedia.org/wiki/Brainfuck )

An interpreter for the language can be found here: https://mitxela.com/other/brainfuck

The entire program can be found in Source.txt

INFO

To begin enter 2 values (either 0 or 1) and the network will process this information and output the XOR value of these two inputs

SPECIF

Network Topology: 2 x 2 x 1: 6 weights and 3 biases

Registers 0-8 will hold these nine values

Registers 9 and 10 will hold the two user inputs

Registers 11 and 12 will hold the weighted sums of the two hidden neurons

Register 13 will hold the final network output

Registers 13-30 are working registers use for in data processing

