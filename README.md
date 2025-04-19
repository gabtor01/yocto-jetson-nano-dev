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
- Git, repo tool, required Yocto dependencies
- NVIDIA Jetson Nano Developer Kit

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/gabtor01/jetson-nano-yocto.git
   cd jetson-nano-yocto
   ```

2. Set up the Yocto environment (depending on the workflow, e.g., `repo`, `kas`, or manual layer setup)

3. Initialize build environment:
   ```bash
   source oe-init-build-env
   ```

4. Build the image:
   ```bash
   bitbake embedded-yocto-custom-image
   ```

5. Flash the built image to an SD card and boot it on the Jetson Nano.

## Project Structure

```
jetson-nano-yocto/
├── docs/                   # Documentation and setup guides
├── meta-custom/            # Custom Yocto layer
├── scripts/                # Helper scripts for build/deploy
└── README.md               # You are here
```

## Documentation

Detailed documentation is provided in the `docs/` directory:

- Setting up the development environment
- Creating and customizing Yocto layers
- Kernel configuration and patching
- Debugging and deployment tips

## Work in Progress

This project is actively evolving as I explore the Yocto ecosystem and embedded Linux for Jetson platforms.
Check the [issues](https://github.com/gabtor01/jetson-nano-yocto/issues) or open one to suggest improvements.

## Contributing

While this is a personal learning project, feel free to fork it, open issues, or propose pull requests.

## License

This project is licensed under the MIT License.
See the [LICENSE](./LICENSE) file for details.
