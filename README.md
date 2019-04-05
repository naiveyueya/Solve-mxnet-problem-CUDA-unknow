# Solve-mxnet-problem-CUDA-unknow
在更新cuda之后，重装了mxnet偶然间撞见的问题
Check failed: e == cudaSuccess || e == cudaErrorCudartUnloading CUDA: unknow
以及Check failed: device_count_ > 0 (-1 vs. 0) GPU usage requires at least 1 GPU
解决办法：大概率是显卡掉了，cuda疯狂更新把显卡驱动给卡出问题了，最好办法就是回滚驱动，然后就能解决了
Check failed: e == cudaSuccess || e == cudaErrorCudartUnloading CUDA: unknow
