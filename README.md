# Asynchronous Parallel Pattern Search (APPS)

Asynchronous Parallel Pattern Search (APPS) Ver. 1.0 uses only function values for optimization, so it can be applied to a wide variety of problems. The name ?pattern search? derives from the fact that a pattern of search directions is used to drive the search. Parallelism is achieved by dividing the search directions (and corresponding function evaluations) among the different processors. The ?asynchronous? part comes about as a consequence of the fact that the search along each direction continues without waiting for searches along other directions to finish. The code is designed to be ported to a variety of  distributed computing platforms, including massively parallel computers. However, the code is not optimized for massively parallel computing. It is primarily aimed at loosely-coupled groups of workstations.

Asynchronous Parallel Pattern Search (APPS) Ver. 1.0 implements an asynchronous and fault tolerant parallel pattern search method for optimization

SCR# 489

Kolda,Tamara G.
