# gIR - GPU-based router
Modern routers need to provide increasing functionalities apart from traditional applications. With the growing internet traffic and complexity of packet processing task, the throughput of routers is affected. We propose gIR, a GPU based intelligent router to improve performance of router by off-loading computationally intensive tasks to GPU.

Recently, GPUs have gone beyond graphics processing to solve scientific applications; they are termed as General Purpose GPUs (GPGPU).The massively-parallel processing power and programming capability of GPU can be used to solve network related problems.
In gIR, we implement some of the core operations of router namely lookup, intrusion detection system for misuse and anomaly detection on a CUDA-enabled GPU. We exploit the inherent data parallelism in packet processing and task-level parallelism pertaining to lookup and intrusion detection system to improve and evaluate the performance of the system.

Team Members: Priya Sundaresan, Sripriya, Yamini
