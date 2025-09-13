# The Undercover Operator
Even if you encrypt all your data (with current methods) when sending it to a server, the server still needs to decrypt your data to actually process it and return a correct result.  This means that while encryption protects your data from middlemen and people intercepting your transmission, you still have to be able to trust the server with your information.

However, there's this fascinating new encryption paradigm called "Fully Homomorphic Encryption" with the special property that math operations done on its encrypted data (cipherwords) will return the correct result (normally, doing this returns nonsense, e.g. decrypt(encrypt(a)+encrypt(b))) is not the same as decript(encript(a))+decript(encript(b)).)  Using fully homomorphic encryption means that a server can use math operations to correctly process your data without ever decrypting it, meaning your information can be private to the server as well!

We've designed a homomorphic encryption method and built a retro-style calculator that can operate on its cipherwords, so everyone can try out this super cool new technique with a familiar tool :)
