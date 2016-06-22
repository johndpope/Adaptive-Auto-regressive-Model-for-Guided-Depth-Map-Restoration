This is the C implementation of the color guided AR model presented in "Color-guided Depth Recovery from RGB-D Data 
Using an Adaptive Auto-regressive Model" in TIP 2014. The original author provided MATLAB source code can be downloaded
here:http://cs.tju.edu.cn/faculty/likun/projects/depth_recovery/index.htm. Our implementation can produce the same results
as theirs. The difference is that we implement the method with C language and sparse matrix which is much faster and can handle
much larger depth maps.


************ how to use **********
run MexFile.m first to compile the cpp file, then run main.m to perform experiments.