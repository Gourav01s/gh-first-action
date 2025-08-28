# gh-first-action
GitHub actions learnings

## created a workflow . added jobs and steps to it
jobs:
  first-job:
    runs-on: ubuntu-latest
    steps:
      - name: Print-greeting
        run: echo "Hello World"
      - name: Print goodbye
        run: echo "Done -bye!"
