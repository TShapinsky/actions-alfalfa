# Alfalfa Action V1

This action creates an instance of [Alfalfa](https://github.com/NREL/alfalfa), that can be used by projects which rely on it.

# Usage

<!-- start usage -->
```yaml
- uses: NREL/alfalfa-action@v1
  with:
    # Docker image tag for pulling Alfalfa containers
    # Default: 'develop' (images generated when develop branch is updated)
    tag: ''

    # Number of workers to run
    # Default: 1
    worker-scale: ''

    # Alfalfa repository ref where compose file can be found.
    # If 'tag' is changed this should point to the correct ref for new tag
    # Default: 'develop'
    compose-file-ref: ''
```
<!-- end usage -->