# Yocto Project for NVIDIA Jetson Nano

Custom embedded Linux development for the Jetson Nano using the Yocto Project.  
This repository documents the configuration, customization, and build process of a Linux distribution tailored for the NVIDIA Jetson Nano Developer Kit.

## Features

- Yocto Project setup and workspace initialization
- Board support and BSP setup for Jetson Nano
- Custom meta-layers for board-specific recipes
- Kernel and device tree configuration
- Driver development and integration
- Reproducible build environment
- Documentation-driven development approach

## Requirements

- Linux-based development host (tested on Ubuntu 20.04)
- Git, required Yocto dependencies
- NVIDIA Jetson Nano Developer Kit
- IMX219 Camera (for driver and application development)

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/gabtor01/jetson-nano-yocto.git
   cd jetson-nano-yocto

