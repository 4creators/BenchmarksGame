Thank you for your interest in contributing to the benchmarks game!


Contribute source-code for measurement
======================================

Your best chance of having source-code accepted is to provide a missing program:
- if the only ~regex-redux program for ~Lua is broken, then fix it;
- if the programs only use one core then provide a program that uses multicore.

(Also consider language implementations like: ~Dart, ~Hack, ~Smalltalk, ~TypeScript).

Your best chance of having source-code accepted is to show that the algorithm is comparable to the other programs, using comments for reviewers.

Style Guide
-----------

Write narrow 80 column programs — someone will try to read on a phone. 

You will probably come across people saying that the programs are not idiomatic ("enough"). So read the [description](https://benchmarksgame-team.pages.debian.net/benchmarksgame/description/summary.html) and write your own idiomatic program, without programming tricks. 

Testing
-------

`diff` program output with the output file provided in the [description](https://benchmarksgame-team.pages.debian.net/benchmarksgame/description/summary.html), to check your program is correct, before you contribute your program. 


Contribute
----------

Please open a new [Contribute Source Code](https://salsa.debian.org/benchmarksgame-team/benchmarksgame/issues/new?issuable_template=Contribute Source Code) issue, and remember to attach your complete tested source-code file.


