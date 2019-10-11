# Cepton SDK

## Overview

The Cepton SDK provides the following features

- **Networking**: Listen for sensor packets.
- **Capture Replay**: Read sensor packets from a PCAP file.
- **Parsing**: Parse sensor packets.
- **Calibration**: Apply sensor calibration.
- **Frame Accumulation**: Accumulate sensor points and detect frames.

Currently, the Cepton LiDAR packet formats are under active development, and are not publicly available. The SDK is required for **Parsing** and **Calibration**. All other SDK features are optional, and can be done manually by the user.

Please read the API documentation at `docs/html/index.html`.

## Installation

To install the executables, run the appropriate installer in `cepton_sdk_redist/setup`.

To clone the entire repository, run

```sh
git clone https://github.com/ceptontech/cepton_sdk_redist.git
```

## Documentation

<https://ceptontech.github.io/cepton_sdk_redist/>

## Getting Started

See `samples`.

## Directories

- **bin**: Executable binaries.
- **cmake**: Extra CMake files.
- **csharp**: C# SDK.
- **docs**: Documentation.
- **driveworks**: NVIDIA DriveWorks SDK.
- **include**: C/C++ Headers.
- **lib**: Library binaries.
- **licenses**: Third party licenses.
- **matlab**: MATLAB SDK.
- **python**: Python SDK.
- **samples**: Sample C/C++ code.
- **setup**: Installers.
- **source**: Partial SDK source code (for reference only).

## Compatibility

The library requires C++11 support.

| OS              | Compiler             | Target          |
| --------------- | -------------------- | --------------- |
| `osx`           | `LLVM 9.1`           |                 |
| `win64`         | `Visual Studio 2017` | `Windows Vista` |
| `linux-i386`    | `gcc-5`              | `Ubuntu 16.04`  |
| `linux-x86_64`  | `gcc-5`              | `Ubuntu 16.04`  |
| `linux-arm`     | `gcc-5`              | `Ubuntu 16.04`  |
| `linux-aarch64` | `gcc-5`              | `Ubuntu 16.04`  |
