# 🖥️ Supercomputer Architecture Analysis – NVIDIA DGX A100 & SuperPOD  
### Machine Learning & Parallel Computing (MLPC) – Group Project

This project provides a full technical analysis of the **NVIDIA DGX A100** and **DGX SuperPOD**, two of the world’s leading high-performance computing (HPC) systems designed for AI, machine learning, and scientific workloads.

The report and poster examine the architecture, components, interconnects, performance benchmarks, scalability, and real-world applications of modern supercomputing.

---

## ⚡ Overview

Supercomputers are essential for cutting-edge research in:
- Artificial Intelligence  
- Climate & weather simulation  
- Drug discovery & protein folding  
- High-energy physics  
- Autonomous driving simulation  

This assignment explores how the **DGX A100** and **SuperPOD** achieve massive parallelism, ultra-fast GPU communication, and extreme scalability.

---

## 🔧 System Architecture

### 🟦 **Core Components**
- **NVIDIA A100 Tensor Core GPUs** (8× per node)
- **AMD EPYC Rome CPUs**
- **High-bandwidth HBM2 memory**
- **NVLink & NVSwitch fabric** for 600 GB/s GPU-to-GPU connectivity
- **Mellanox HDR InfiniBand** (200 Gb/s) inter-node communication
- Multi-tier NVMe storage system

### 🟩 **DGX SuperPOD Scaling**
- Modular cluster architecture  
- Multiple DGX A100 nodes connected through InfiniBand switches  
- Supports petaflops-scale AI training  
- Near-linear performance scaling for distributed workloads  

### 🟧 **Parallel Computing Concepts Covered**
- GPU parallelism (CUDA cores, Tensor Cores, SIMD execution)
- Multi-GPU communication (NVLink/NVSwitch)
- HPC networking topologies  
- Distributed training & task scheduling  
- Mixed-precision acceleration (FP32, FP16, BF16, TF32)

---

## 📊 Performance & Benchmarks

The project analyzes benchmark indicators such as:
- **Rmax / Rpeak performance**
- **HPL & HPCG results**
- **MLPerf AI benchmarking**
- **FLOPS/W efficiency metrics** (Green500)

Key findings highlight how the A100 architecture leads in:
- Deep learning training throughput  
- Energy efficiency  
- HPC scientific workloads  
- Memory bandwidth and tensor performance  

---

## 🌍 Real-World Use Cases

### 🧬 Scientific Research
- Protein folding and COVID-19 drug simulation  
- Climate and environmental modeling  

### 🚗 Autonomous Systems
- Reinforcement learning  
- 3D simulation engines  
- Full self-driving model training  

### 🤖 Artificial Intelligence
- Large language model (LLM) training  
- Computer vision  
- Generative AI  

### 🧪 High-Performance Data Analytics
- Weather prediction  
- Physics experiments  
- Seismic and geological modeling  

---

## 🧠 Skills Demonstrated

- Understanding of **HPC architecture**
- GPU computing fundamentals  
- Parallel & distributed processing concepts  
- HPC interconnects & networking  
- Storage hierarchy & I/O optimization  
- Benchmark interpretation (HPCG, HPL, MLPerf)
- Research analysis & poster design  
- Technical documentation and reporting  

---

✨ *This project showcases my understanding of modern supercomputing, GPU acceleration, parallel processing, and HPC system design — key foundations for AI, machine learning, and large-scale computation.*
