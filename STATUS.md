# STATUS

## Badges Applying For

- Artifacts Available
- Artifacts Functional
- Artifacts Reusable

## Justification

### Artifacts Available

The ORBiS artifact is publicly accessible through GitHub and has been permanently archived on Zenodo with the following DOI:

[https://doi.org/10.5281/zenodo.21767392](https://doi.org/10.5281/zenodo.21767392)

The archived artifact includes the ORBiS source code, benchmark programs, target-specific data, experimental results, Dockerfile, and documentation required to access and use the artifact.

### Artifacts Functional

The artifact provides a complete and executable environment for running ORBiS and validating the main functionality described in the paper.

- A pre-built Docker image is provided with ORBiS and all required dependencies installed.
- A Dockerfile is provided for building the environment from source.
- Benchmark programs, option dictionaries, and option-related branch data are included.
- A smoke test with a 360-second symbolic-execution budget can be completed within 30 minutes.
- Scripts are provided for reporting branch coverage and detected bugs.

By following the instructions in `README.md`, reviewers can run ORBiS, generate test cases, and inspect the resulting branch-coverage data.

### Artifacts Reusable

The artifact is designed to support reuse and extension by other researchers.

- The implementation is organized into separate components for ORBiS, benchmark construction, tracing, data, and result analysis.
- The tracer can be used to generate option dictionaries and option-related branch information for additional target programs.
- Benchmark build scripts and experiment configurations are provided.
- The repository includes instructions for running ORBiS on the supplied benchmarks and for preparing new configurable command-line programs.
- Experimental data and result-processing scripts are provided in machine-readable formats.

These materials allow researchers to reproduce the provided experiments, study the implementation, and apply ORBiS to additional programs beyond those evaluated in the paper.
