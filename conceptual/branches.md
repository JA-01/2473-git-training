# Branches and Merging - what version of the codebase are we working on?

When working on a project, we can have different "versions" of the project, each called a 'branch'.

Some examples include

- main, called 'main'
- a branch to test mechanism values, could be called 'dev/week-4/sharvil/mech-testing'
- a a branch off of the previous branch to tune the climber: 'dev/week-4/sharvil/climber-tuning'

```
||
|/
|
```
A branch allows us to take the codebase at a specific point, and stop recieving changes past that point.

This allows us to take the branch, work on whatever subproject we need to write, then add it back to the parent branch when we're ready.

During that time, the branches may diverge - they both change the same files, so they can't automatically be added together. This is called a merge conflict.

You'll see something like this:

```
========>HEAD 1
code changes
========>HEAD 1
other code changes
======<TAIL
```

It is then up to the the coder to reslove the merge (pst... VSCode will help you!) and then they can push a merged version of the branch so that the branches changes are combined into the original branch.


