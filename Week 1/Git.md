Git is distributed version control system.

## Need of Git?

In real world scenario, there are hundreds of files & packages & many people are working on it simultaneously. So we need a tool to track these files - see things like who created the file, who updated, what was updated, who deleted, what was deleted from the file, etc.

## Git branching strategy

Primary goal of an organization is to ensure that customer gets releases on time & frequently.

So for this, we need a proper & effective branching strategy.

## Why branching?

Any new changes should not effect our existing application, it should be added only after proper testing.

Branches are created to fix a particular bug & after testing, the branch is merged

## .git

Its responsible for tracking files & directories. Here we have a directory called hooks, in this we can write a pre-commit if we want to avoid pushing sensitive data.

### git add is used to add a file for tracking.
