
```
rocprof run.sh 
RPL: on '191105_165702' from '/opt/rocm/rocprofiler' in '/home/test'
RPL: profiling 'run.sh'
RPL: input file ''
RPL: output dir '/tmp/rpl_data_191105_165702_27576'
RPL: result dir '/tmp/rpl_data_191105_165702_27576/input_results_191105_165702'
ROCProfiler: input from "/tmp/rpl_data_191105_165702_27576/input.xml"
  0 metrics
  0 traces
Loss: 0.000474 after 553 batches
==> Learned function:   y = +2.32 x^4 -5.08 x^3 -9.16 x^2 +3.31 x^1 -5.40
==> Actual function:    y = +2.37 x^4 -5.06 x^3 -9.17 x^2 +3.30 x^1 -5.41

ROCPRofiler: 8291 contexts collected, output directory /tmp/rpl_data_191105_165702_27576/input_results_191105_165702
RPL: '/home/test/results.csv' is generated
```
