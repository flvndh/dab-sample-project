# DAB sample project

## Requirements

* Databricks CLI v0.221.1
* [Poetry](https://python-poetry.org/) 1.8.3
* DATABRICKS_HOST
* DATABRICKS_TOKEN

## Steps to reproduce

To reproduce the issue, run the following commands:

```bash
./Taskfile step 1
./Taskfile step 2
```

## Expected outputs

Step 1:

```
Executing job 1
```

Step 2:

```
AttributeError: module 'dab_sample_project' has no attribute 'job_2'
```
