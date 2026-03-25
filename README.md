# IndustrialEdge-LoadBalancer

A deep learning-based load balancing system for edge-driven industrial automation, featuring real-time contour detection and motor load optimization.

## Overview

This repository contains the implementation of a deep learning-based online load balancing method for industrial motor control systems. The system integrates real-time sensor data analysis with dynamic load optimization, enabling autonomous decision-making at the edge device level.

### Key Features

- **Domain-Adapted Contour Extraction**: Fine-tuned BASNet model for pressure sensor data processing
- **Real-Time Load Balancing Algorithm**: Dynamic motor load distribution optimization
- **Edge Deployment Ready**: Optimized for NVIDIA Jetson Xavier NX with FP16 inference
- **RTOS Integration**: FreeRTOS-based task management with priority message handling

## Installation

### Requirements

- Python 3.8+
- PyTorch 1.9+
- TensorRT 8.0+ (for edge deployment)
- FreeRTOS (for embedded systems)

- 
