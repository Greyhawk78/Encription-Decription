# Encription-Decription
Simple encript-decript programm. Works with command line arguments.

Syntax 
Command line arguments

-alg [shift] [unicode] <br />
Choosing shifting algorithm <br />
First algorithm shifts each letter by the specified number according to its order in the alphabet in circle. <br />
The second one  based on Unicode table. <br />

-in 
-out <br />
specify the full name of a file to read data and to write the result.

-mode [enc] [dec] <br />
Determine the program’s mode (enc - encryption, dec - decryption). 

-key [int] <br />
Argument is an integer key to modify the message.

-data [String] <br />
text or ciphertext within quotes to encrypt or decrypt. <br />

If there is no -mode, the program work in enc mode. <br />
If there is no -key, the program  consider that key = 0. <br />
If there is no -data, the program assume that the data is an empty string. <br />
If there is no -out argument, the program print data to the standard output. <br />
If there are both -data and -in arguments, program prefer -data over -in. <br />
If there is no -alg program default it to shift. <br />
