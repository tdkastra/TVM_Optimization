# TVM_Optimization
Engineered custom Apache TVM schedules and dual-issue ARMv8 NEON microkernels (loop unrolling, NWC cache alignment, static AoT memory planning) for a 1D-CNN on Cortex-A53, achieving 1.27 ms inference latency (1.5× faster than ONNX Runtime), 50% lower L1 traffic, 4.7× less jitter, and a 70× smaller (362 KB) zero-heap standalone binary.
