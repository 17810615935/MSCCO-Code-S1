Code S1. MATLAB source code for the MSCCO manuscript

Software
  MATLAB R2025a
  The MathWorks, Inc., Natick, MA, USA
  https://www.mathworks.com

Computer used to identify the installed environment
  13th Gen Intel Core i9-13900H, 16 GB RAM, 64-bit Windows 11 Home

What is included
  CEC2017_comparison/Dim30, Dim50, Dim100
    Benchmark comparison. Entry script: run_tol1.m
    Population size 30, maximum iterations 500, 30 independent runs.
    The script evaluates F1-F30. The manuscript excludes F2 from ranks
    and statistical comparisons because that function is unstable.
  Ablation/Dim30, Dim50, Dim100
    Ablation of the three MSCCO strategies. Entry script: run_tol1.m
    Compared variants: MSCCO_wo1, MSCCO_wo2, MSCCO_wo3, and MSCCO.
    Same population size, iteration budget, and run count as the benchmark.
  MultiUAV
    Four urban delivery scenarios. Entry scripts: main.m (one scenario)
    and run_all.m (the scenario comparison).
    Population size 30, maximum iterations 500, 10 independent runs
    in the manuscript experiments.
  input_data17
    CEC2017 shift, rotation, and shuffle data required by cec17_func.mexw64.
    One copy is supplied. Before running a CEC2017 or ablation folder,
    copy input_data17 into that folder so it sits beside run_tol1.m.

Not included
  Previously generated result workbooks, figures, and .mat result files.
  Those outputs are replaced by Tables S1-S5 for the published results.
