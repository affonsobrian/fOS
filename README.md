# fOS

**fOS** is a simple operating system designed for learning and experimentation. It's a minimal OS built from scratch, with no additional complexities or features beyond the basics of an operating system.

## Features

- Minimal kernel
- Basic bootloader
- Runs on x86_64 architecture

## Getting Started

To build and run fOS:

### Prerequisites

- A cross-compiler for your architecture (e.g., GCC)
- QEMU for testing, or physical hardware (for advanced users)

### Build fOS

1. Clone the repository:

    ```bash
    git clone https://github.com/affonsobrian/fOS.git
    cd fOS
    ```

2. Build the OS:

    ```bash
    make
    ```

3. Run it with QEMU:

    ```bash
    make run
    ```
