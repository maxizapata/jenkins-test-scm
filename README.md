# jenkins-test-scm
Simple project for do my jenkins labs.

## Build triggers
### Go to Project -> Build Trigers tab
- Build periodically
Schedule tags:
    - @daily
    - @montly

The difference between periodically and Poll repo and build periodically is that periodically builds the project even if not has been changes, Poll repo only builds when it find a new commit with changes in the code.

