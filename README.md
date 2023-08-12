# oxipage.github.io
Historical pages from my academic hardware compilation website at Oxford.

The materials in these pages were developed in the period 1990-2000 when I formed and ran the Hardware Compilation Research Group at the University of Oxford.
The main focus was my language Handel. This was designed as low-level programming language capable of easy compilation to digital hardware, such that the programmer had excellent control over both space (the hardware gates) and time (clock-cycle accurate execution of the program). Crucially, no knowledge of digital hardware was necessary to write programs in Handel. This ensured that Handel programs were completely into the space of algorithmic programs, rather than hardware descriptions.

For most of this period the language existed in an abstract syntax form, embedded in the SML language. This was deliberate as the programs could be transformed into hardware by a series of (eventually provably correct) language transformations. By the same token, the level of the language could be raised arbitrarily higher by defining functions (within individual programs, or libraries) which would re-write higher-level constructs into Handel.

The Handel language was re-implemented as Handel-C (i.e. Handel with a concrete, C-like, syntax) when it was exploited commercially by a spinout company. 
Handel-C was later transferred into another company which failed soon after, marking the end of its availability as a commercial language.
