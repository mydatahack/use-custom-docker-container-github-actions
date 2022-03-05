# Running a job in a custom container

This repo is for testing Github Actions🧚🏼‍♀️

We can run a job in a container: https://docs.github.com/en/actions/using-jobs/running-jobs-in-a-container

Use this:

```yml
jobs:
  run-in-container:
    runs-on: ubuntu-latest
    container: alpine-node:16
```

instead of this:

```yml
jobs:
  run-in-vm:
    runs-on: ubuntu-latest
```
