# Parameter-Optimization

This is the repository for Parameter Optimization

Dataset used:
default of credit card clients Data Set

Dataset description

Number of Instances:30000

Number of attributes:24

Missing values:NA

Dataset Charactersticss:MULTIVARIATE

Attribute Characterstics:Integer, Real


SAMPLES VS ACCURACY TABLE WITH BEST PARAMETERS

accuracy	kernel	C	gamma
0	0.227667	sigmoid	0.063954	0.515928
1	0.761	poly	0.180378	0.105685
2	0.294333	linear	0.011117	0.108192
3	0.23	rbf	0.963298	0.043466
4	0.235	rbf	0.992294	0.837051
5	0.254	poly	0.49067	0.77794
6	0.265333	sigmoid	0.405466	0.516282
7	0.788	sigmoid	0.873376	0.406356
8	0.767	sigmoid	0.762497	0.457946
9	0.265333	sigmoid	0.187274	0.224679

BEST SAMPLE:7th

BEST ACCURACY:0.788

BEST PARAMETERS: KERNEL-SIGMOID, C-0.873376,gamma:0.406356


SAMPLE 5 ACCURACY VS ITERATIONS PLOT(ITERATIONS UPTO:1000)
![image](https://user-images.githubusercontent.com/112539712/233225461-6ce9f4a1-699d-48af-9de3-94eda4ee8400.png)
