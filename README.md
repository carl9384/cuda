# CUDA resources
Useful resources for learning CUDA and its Python variants.

### Numba (CUDA-Python)
Numba provides a framework for quickly implementing GPU acceleration. Numba does not support all CUDA functionality but has a simpler implementation than PyCUDA. Kernels are written in Python (technically the CUDA-Python variant) and converted by the Numba compiler to PTX code.
http://numba.pydata.org/numba-doc/0.13/CUDAJit.html

### PyCUDA Documentation
PyCUDA framework provides complete CUDA functionality, however this may require writing kernels in CUDA C. 
https://documen.tician.de/pycuda/

### Parallel for all NVIDIA blog (Excellent)
Excellent discussion of various parallel programming concepts, problems, and solutions.
https://devblogs.nvidia.com/parallelforall/using-shared-memory-cuda-cc/

### Optimizing parallel reduction in CUDA (Excellent)
An excellent resource produced by NVIDIA for understanding reduction algorithms, and the different sources of both acceleration and bottlenecks in a parallel processing framework. 
http://developer.download.nvidia.com/compute/cuda/1.1-Beta/x86_website/projects/reduction/doc/reduction.pdf

### Dot product, matrix-vector multiplication, sparse matrix multiplication, global reduction
http://people.cs.pitt.edu/~melhem/courses/xx45p/cuda_examples.pdf

### Reductions and low-level performance considerations
https://mc.stanford.edu/cgi-bin/images/5/55/Darve_cme343_cuda_4.pdf


### Django/Celery/PyCuda troubleshooting
https://stackoverflow.com/questions/24744755/why-am-i-getting-cumemalloc-failed-not-initialized-even-though-i-am-initializ
