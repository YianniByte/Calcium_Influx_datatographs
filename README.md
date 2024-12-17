This is a script to convert raw photon counting data from 96-well plates into 5 types of graphs. 
Most appropriate data source for these graphs is from Varioskan plate reader experiments.

1. Line graph comparing relative light units vs time.
2. Comparison of treatments to respective mock controls (if many treatments with equal number of mocks).
3. Cumulative RLU between treatments (any user defined factor): Within the user defined time scale
  a. Statistics for comparing factors.
4. Ratio of RLU to baseline/background RLU (If high background RLU is affecting experiment).
  a. Must have additional photon baseline data for this (data recorded before addition of .
5. L/Lmax calcium discharge graph.
  a. Must have additional calcium discharge data for this.


Information on what packages to use and workflow are described in each segment.
In each, choose between randomly generated table or your own excel dataframe (script to extract is given).
If an error occurs in the middle of a section, start from the begining of the type of graph you want to make.
