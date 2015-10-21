Sparse matrices which don't fit in RAM need special treatment as far as decomposition is concerned.  Parallelizable and/or stream-oriented algorithms are needed.

Currently implemented: Singular Value Decomposition using the Asymmetric Generalized Hebbian Algorithm outlined in Genevieve Gorrell & Brandyn Webb's paper: http://www.scribd.com/doc/7017586/Gorrell-Webb

Additionally, there is a Lanczos implementation, both single-threaded, and in the contrib/hadoop subdirectory, as a hadoop map-reduce job.