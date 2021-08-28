# HT_tensor_learning_using_GPU_tensor_cores
This repository contains applications for HT tensor learning using GPU tensor cores, including HT tensor decompostion, HT tensor layer and TTN algorithm. 

## File structure

> HT_tensor_learning_using_GPU_tensor_cores
>> third_order_tensor_decompsition
>>> baseline ----- unoptimized <br>
>>> opt ---------- optimized <br>
>>> large -------- using TSQR algorithm <br>

>> fourth_order_tensor_decomposition
>>> multiple_GPUs ----- using shard mode <br>
>>> single GPU
>>>> baseline ----------unoptimized <br>
>>>> opt ---------------optimized <br>


>> HT_tensor_layer
>>> mnist.py  ----- fully connect <br>
>>> mnist_ht.py ----- HT tensor layer <br>
>>> mnist_half.py ----- HT tensor layer using apex <br>

>> TTN
>>> cuda_baseline            ----- unoptimized <br>
>>> cuda_unitree_tensorcore  ----- optimized <br>
>>> groundstate_example.py   ----- TensorNetwork-JAX <br>
