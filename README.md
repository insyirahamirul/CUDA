# CUDA


1) 3 ways to accelerate programs on GPU : Libraries, GPU directives, Programming languages.

2) CUDA (Compute Unified Device Architecture) is a programming language by NVIDIA for NVIDIA GPUs. 

3) Running : 

To execute CUDA program, NVIDIA CUDA Compiler (NVCC) must be installed to separate CPU (host) and GPU (device) code within the program. The host code will be passed to C compiler (like GCC) while the device code is further compiled by NVCC. 

Download link : https://developer.nvidia.com/cuda-downloads

4) Debugging :

When developing massively parallel applications on the GPU, you need a debugger capable of handling thousands of threads running simultaneously on each GPU in the system. CUDA-GDB supports debugging of both 32 and 64-bit CUDA C/C++ applications. 

Download link : https://developer.nvidia.com/cuda-gdb

5) Optimization : 

NVIDIA Visual Profiler is a cross-platform performance profiling tool that delivers developers vital feedback for optimizing CUDA C/C++ applications. Visual Profiler supports all 350 million+ CUDA capable NVIDIA GPUs shipped since 2006 on Linux, Mac OS X, and Windows.

Download link : https://developer.nvidia.com/nvidia-visual-profiler
