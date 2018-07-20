Contribute source-code for measurement
======================================

Although we are usually happy to accept better programs, your best chance of having source-code accepted is to provide a missing program:
- if the only ~regex-redux program for ~Lua is broken, then fix it;
- if the programs only use one core then provide a program that uses multicore.

(Also consider language implementations like: ~Dart, ~Hack, ~Smalltalk, ~TypeScript).

Your best chance of having source-code accepted is to show that the algorithm is comparable to the other programs, by using code comments to explain

Style Guide
-----------

Write narrow 80 column programs — someone will try to read on a phone. 

You will probably come across people saying that the programs are not idiomatic ("enough"). So read the [description](https://benchmarksgame-team.pages.debian.net/benchmarksgame/description/summary.html) and write your own idiomatic program, without programming tricks. 

Test your program!
------------------
Check that program-output matches expected-output before upload.

Use `diff` to check that whitespace characters match.

`diff` program-output with the output-file provided in the [description](https://benchmarksgame-team.pages.debian.net/benchmarksgame/description/summary.html).


Upload a COMPLETE TESTED source-code file
-----------------------------------------

Open a new [Contribute Source Code](https://salsa.debian.org/benchmarksgame-team/benchmarksgame/issues/new?issuable_template=Contribute Source Code) issue.

Attach your COMPLETE TESTED source-code file.

(patch files will not be accepted.)



