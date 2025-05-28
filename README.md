# Power PMAC Buffer Handler via User Shared Memory

## Overview

This module provides a buffer management system for Power PMAC shared memory (USHM). It allows structured access to shared memory using a flexible frame-based approach, supporting both `int` and `double` data types. The buffer is designed to be used in conjunction with TCP servers or other data acquisition systems.

## Features

- Frame-based memory layout using a union type (`Point`) for mixed-type data.
- Alignment utilities to ensure proper memory access.
- Functions to initialize, write, and test shared memory buffers.
- Designed for use in Power PMAC Background Programs or Libraries.
- Compatible with other modules like `ppmac_tcp_server` for real-time data streaming.

## How to Use

Follow the steps below to add this module to your Power PMAC project:

1. Clone or add this repository as a submodule in the desired path under **C Language**.
2. In the Power PMAC IDE, right-click on the desired folder (e.g., *Background Programs* or *Libraries*) and select **"Add a new..."**.
3. Enter the name `ppmac_ushm_buffer` — the same name as this repository.
4. When prompted to overwrite the file, select **"No"**.
5. Right-click on the created folder and select **"Add" > "Existing item..."**.
6. Select the source (`.c`) and header (`.h`) files from this repository.

## License

This project is licensed under the Apache 2.0 License. See the LICENSE file for details.

## Author

[Leandro Martins dos Santos](https://github.com/LeandroMartinsdS) <br>
Software Systems Engineer <br>
Diamond Light Source Ltd. <br>
