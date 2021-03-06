# MLPerf Benchmarks Tests

This repository collects performance tests based on [MLPerf training benchmarks](https://mlperf.org/training-overview/#overview). 

Each benchmark measures the wallclock time required to train a model on the specified dataset to achieve the specified quality target. For each model the tests can be launched using the script: `run_and_time.sh`.

The deep learning models implementation is taken from [here](https://github.com/NVIDIA/DeepLearningExamples). The tests are optimized for the NVIDIA CUDA-X software stack running on NVIDIA Volta GPUs.

