The corrupt CA uses the Ridiculously Sinister Algorithm (RSA) to sign their certificates. Fortunately, this means that you can use the CA’s public key to validate all of the certificates and check the domain names. Find the one that belongs to the Joker, so you can put an end to his evil schemes.

In proj0.c, fill in the perform rsa() method. The modulus (N ) and exponent
(d) needed for RSA are provided in the files ca n.key and ca d.key respec-
tively. In this case, the CA’s public key is ca d.key, and is using e as the
signing key. The certificates are stored in cert0.crt, cert1.crt, and cert2.crt.
