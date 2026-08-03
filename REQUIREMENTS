# REQUIREMENTS

## Hardware Requirements

- Minimum: 8 GB RAM
- Recommended: 16 GB RAM or more
- Storage: At least 20 GB of free disk space for the Docker image, container, and experiment outputs
- Architecture: x86-64

## Software Requirements

- Operating System: Linux, macOS, or Windows with Docker support
- Docker: Required
- Internet connection: Required to download the Docker image

## Docker Image

Pull the pre-built Docker image:
```bash
docker pull minjongkim99/orbis-ase26:v1.1
```

Run the container:
```
docker run --rm -it --ulimit stack=-1:-1 minjongkim99/orbis-ase26:v1.1 /bin/bash
```

## Dependencies
- All required dependencies, including ORBiS, Python, LLVM, KLEE, STP, and the benchmark programs, are pre-installed in the Docker image.
- No additional installation is required when using Docker.

## Execution Time

- Smoke test: approximately 10–20 minutes
- Symbolic-execution budget for the smoke test: 360 seconds
- Full experiments may require several hours or longer depending on the target program and hardware

## Known Limitations
- The artifact is primarily tested on x86-64 Linux.
- ARM-based systems, including Apple Silicon, are not officially supported.
- Experimental results may vary slightly depending on system load and hardware.
