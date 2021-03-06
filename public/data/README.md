data files
==========

The program measurements are stored in plain text, comma separated value, spreadsheet compatible files - with a column-header row:

- name — the label used to identify one of the tasks
- lang — the label used to identify one of the language implementations
- id — the label used to identify a specific program that implements a task for a language implementation
- n — the workload
- size(B) — the size in bytes of the GZip compressed source-code file
- cpu(s) — the `usr+sys rusage` seconds
- mem(KB) — `GLIBTOP_PROC_MEM_RESIDENT` 
- status — negative values indicate the program failed in some way
- load — the proportion of `GTop cpu not-idle` to `GTop cpu total` for each core
- elapsed(s) — the elapsed `time.time()` seconds


data.csv
--------

Just the fastest measurements at the largest measured workloads.

ndata.csv
---------

Just the fastest measurements at all measured workloads.


alldata.csv
-----------

All measurements, including repeated measurements.


How programs are measured
-------------------------

Please refer to the benchmarks game website for [more details](https://benchmarksgame-team.pages.debian.net/benchmarksgame/how-programs-are-measured.html) of the measurement process, [task descriptions](https://benchmarksgame-team.pages.debian.net/benchmarksgame/description/summary.html), and comparisons of [program measurements](https://benchmarksgame-team.pages.debian.net/benchmarksgame/which-programs-are-fastest.html).


