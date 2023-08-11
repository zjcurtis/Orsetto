# Orsetto
Distributed relational programming language for the real world.

# tl;dr?
BEAM/OTP is great, single threading/hard failure is not. Types are also great because lol efficiency. What if BEAM/OTP ran on WAS(M/I)? 

Relational programming is great, but is unwieldy in many cases. Types and modes help here.

CUE has a nice solution to this, a type/value lattice. With Orsetto I want to shamelessly steal that, and make programming a proof search over that lattice. This should parallelize reasonably well.
