# gh-first-action
GitHub actions learnings

## Created a workflow 
Added jobs and steps to it.
```bash
jobs:
  first-job:
    runs-on: ubuntu-latest
    steps:
      - name: Print-greeting
        run: echo "Hello World"
      - name: Print goodbye
        run: echo "Done -bye!"
```

## To run multiple shell commands 
By adding the pipe symbol (|) as a value after the run: key.
```bash
run: |
    echo "First output"
    echo "Second output"
```
This will run both commands in one step.

## Next part is in " second-action-react-demo " repository
Added reat-demo project so more operations can be performed and practiced <br/>
creating workflows which run automatically after each update
