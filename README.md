# VeriStand Model Generation Support

Use VeriStand Model Generation Support to create VeriStand compatible models within the MathWorks Simulink® environment.

You can generate models for Windows Desktop or NI Linux Real-Time platforms. Once generated, [VeriStand](https://www.ni.com/veristand) can import and deploy the model to a target.

## VeriStand and MathWorks MATLAB® Release Compatibility

| VeriStand | MathWorks MATLAB® | VeriStand Model Generation Support |
|:-|:-|:-|
| 2023 Q1 | R2022a/b <br> R2021a/b <br> R2020a/b          | [1.2](https://github.com/ni/niveristand-model-generation-support-for-simulink/releases/tag/v1.2.1), 1.1*, 1.0* |
| 2021 R3 | R2022a/b <br> R2021a/b <br> R2020a/b          | [1.2](https://github.com/ni/niveristand-model-generation-support-for-simulink/releases/tag/v1.2.1), 1.1*, 1.0* |
| 2021 R2 | R2022a <br> R2021a/b <br> R2020a/b          | [1.1](https://github.com/ni/niveristand-model-generation-support-for-simulink/releases/tag/v1.1.0), 1.0* |
| 2021    | R2021a/b <br> R2020a/b                      | [1.0](https://github.com/ni/niveristand-model-generation-support-for-simulink/releases/tag/v1.0.0) |

*Previous versions of VeriStand Model Generation Support are compatible with newer versions of VeriStand, but may not include the newest features.

## Installation Guide for VeriStand Model Generation Support

Before you begin, install the supported versions of MathWorks MATLAB®, Simulink®, MATLAB® Coder™ and Simulink® Coder™.

### Install VeriStand Model Generation Support

1. Open the MATLAB Add-On Explorer.
1. Use the search bar to find **VeriStand Model Generation Support**
1. Install the add-on.
1. Restart MATLAB.

**Note:** You should uninstall the Veristand Model Framework package before using the VeriStand Model Generation Support add-on.

### Install the MATLAB MinGW Compiler for 64-bit Windows targets

1. Open the MATLAB Add-On Explorer.
1. Search for [MATLAB Support for MinGW-w64 C/C++ Compiler](https://www.mathworks.com/matlabcentral/fileexchange/52848-matlab-support-for-mingw-w64-c-c-compiler).
1. Install the compiler.
1. Restart MATLAB.

### Install the NI GCC Cross-Compiler for NI Linux Real-Time targets

1. Download and install [C/C++ Development Tools for NI Linux Real-Time 2017, Eclipse Edition](https://www.ni.com/en-in/support/downloads/software-products/download.c-c---development-tools.html#333407).
1. Restart MATLAB.
