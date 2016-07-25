# STREAM_tests
Sample code for STREAM: Sustainable Memory Bandwidth in High Performance Computers based on John D. McCalpin's work (http://www.cs.virginia.edu/stream/)


The STREAM benchmark is a simple synthetic benchmark program that measures sustainable memory bandwidth (in MB/s) and the corresponding computation rate for simple vector kernels. Computer cpus are getting faster much more quickly than computer memory systems. As this progresses, more and more programs will be limited in performance by the memory bandwidth of the system, rather than by the computational performance of the cpu. As an extreme example, several current high-end machines run simple arithmetic kernels for out-of-cache operands at 4-5% of their rated peak speeds --- that means that they are spending 95-96% of their time idle and waiting for cache misses to be satisfied.

The STREAM benchmark is specifically designed to work with datasets much larger than the available cache on any given system, so that the results are (presumably) more indicative of the performance of very large, vector style applications.

Related Work:
http://www.cs.virginia.edu/~mccalpin/papers/bandwidth/bandwidth.html
http://www.cs.virginia.edu/~mccalpin/papers/balance/index.html
