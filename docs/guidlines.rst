***********************
Guidlines
***********************
Remember that
===============================
Remember that L :=2^n So sum of appearance of each symbol must be power of 2. In order to use encoder/decoder you must first fill up config filles.

What our project contains
===============================

Encoder file
-------------
* Core.h - declarations of functions.
* Core.c - definitions of functions.
* main.c - encoder function, which calls functions from Core.c
* main_test.c - example how use encoder.
* config - . First column consist letters from our alphabet, range:0 - 255(filled by you). Second column consist number of appearances.
* symbols - first line consist starting state of encode then, sequence of symbols, we want to code.(filled by you).

Decoder file
-------------
* Bits.txt - sequence of bits we encoded within our coder ( encoder fills it ).
* Core.c - definitions of functions.
* Core.h - declarations of functions .
* Nsymbols.txt - Alphabet size ( filled by you).
* Numbers.txt - Number of appearances for each letter. ( filled by you ).
* test_bench.c - main function calling decodingfunction.
* numberofBits.txt - Number of Bits we coded ( encoder fills it ).
* state.txt - starting state for decoder, ending state for encoder(encoder fills it ).
* symbols.txt - reversal sequence of decode symbols, and starting state for encoder.


