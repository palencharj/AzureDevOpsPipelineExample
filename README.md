# Azure DevOps Pipeline Example

This repository is a small example showing how to run a Python script in an Azure DevOps pipeline while using GitHub as the source repository.

The pipeline runs `build_test_artifact.py`, which creates a simple text file in the `output/` directory. Azure DevOps then publishes that directory as a pipeline artifact named `example-output`.

## Run locally

```bash
python3 build_test_artifact.py
```

The generated file will be written to:

```text
output/example-artifact.txt
```
