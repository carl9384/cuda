# CUDA resources
Useful resources for learning CUDA and its Python variants.

### Numba (CUDA-Python)
Numba provides a framework for quickly implementing GPU acceleration. Numba does not support all CUDA functionality but has a simpler implementation than PyCUDA. Kernels are written in Python (technically the CUDA-Python variant) and converted by the Numba compiler to PTX code.
http://numba.pydata.org/numba-doc/0.13/CUDAJit.html

### PyCUDA Documentation
PyCUDA framework provides complete CUDA functionality, however this may require writing kernels in CUDA C. 
https://documen.tician.de/pycuda/

### Dot product, matrix-vector multiplication, sparse matrix multiplication, global reduction
http://people.cs.pitt.edu/~melhem/courses/xx45p/cuda_examples.pdf

### Reductions and low-level performance considerations
https://mc.stanford.edu/cgi-bin/images/5/55/Darve_cme343_cuda_4.pdf

### Optimizing parallel reduction in CUDA (Excellent)
http://developer.download.nvidia.com/compute/cuda/1.1-Beta/x86_website/projects/reduction/doc/reduction.pdf

### Django/Celery/PyCuda troubleshooting
https://stackoverflow.com/questions/24744755/why-am-i-getting-cumemalloc-failed-not-initialized-even-though-i-am-initializ
