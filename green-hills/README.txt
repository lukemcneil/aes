Author: Luke McNeil

This is an implementation of the AES (Rijndael) symmetric key
encryption algorithm. AES is the most common symmetric key encryption
algorithm used today. This algorithm takes in a plaintext input to
encrypt as well as a key, and prints the resulting encrypted
message. This implementation uses cipher-block chaining (CBC) mode.

To run, do "make", and then run "./aes numIterations numRounds
keyFileName plaintextFileName". The first two arguments are parameters
to AES telling it how many times to perform certain steps of the
encryption (these can be integers such as 10). The last two arguments
are the filenames of the files containing a 128 bit key and a
plaintext of any length respectively.
