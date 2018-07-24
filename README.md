# cudaForHackers
Some hacks to try when you just want cuda up and running

# Tensorflow GPU not working
Add the CUDA installation to your path

# CUDA driver not supported by runtime
Deal with the CUDA driver version and the CUDA runtime version. 
Ensure there are no mismatches according to this post:

https://stackoverflow.com/questions/30820513/what-is-version-of-cuda-for-nvidia-304-125/30820690#30820690


CUDA runtime version can be checked via nvcc --version, while CUDA driver version is checked via `nvidia-smi`. Finally, *be sure to update the CUDAtoolkit version associated with Tensorflow* (for this I strongly recommend you use an environment manager!) 
