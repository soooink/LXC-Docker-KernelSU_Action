# Product Overview

LXC-Docker-KernelSU_Action is a GitHub Actions-based kernel compilation system for Android devices. It provides automated kernel building with support for:

- **KernelSU**: Root solution for Android devices
- **LXC/Docker**: Container support for Android kernels  
- **Multiple Toolchains**: Comprehensive collection of compilation toolchains including AOSP Clang, LLVM, ARM GCC, Proton-clang, and others
- **Non-GKI Kernels**: Specifically designed for older kernel versions (4.9, 4.14, 4.19, 5.4)

The project enables users to build custom kernels for their Android devices without requiring local development environments, using GitHub's CI/CD infrastructure for compilation.

## Target Users
- Android kernel developers
- Device maintainers  
- Users seeking KernelSU support for their devices
- Developers working with containerization on Android

## Key Features
- 18 different workflow configurations for maximum build success rate
- Support for various Android versions and kernel configurations
- Automated AnyKernel3 packaging
- Extensive toolchain compatibility matrix