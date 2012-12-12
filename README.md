ORGINAL URL: https://code.google.com/p/js-mcrypt/

This class allows a common interface to encrypt extended ascii strings with various modes of operation. Currently supported are:

ecb
cbc
cfb
ncfb
nofb
ctr

The block encryption is handled by external classes, making this class extensible Currently the block ciphers used are:

rijndael-128
rijndael-192
rijndael-256
serpent

This is compatible with php's mcrypt
Demo: http://crazycode.doerings.org/js-mcrypt/