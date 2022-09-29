# conda-in-subfolder

Install a conda environment with caching that is in a subfolder of your GitHub project

## Usage

Use like

```yaml
...
jobs:
  steps:
    ...
    - name: Setup Conda Env
      uses: djohn156/conda-in-subfolder@v1
      with:
        path: path/to/python/project
        env-name: my-env-name
    ...
```

### Optional parameters

By changing the `cache-number`, you can force the action to refresh the cache.
