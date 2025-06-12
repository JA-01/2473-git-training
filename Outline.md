# 2025 Git Training: Rough Outline

1. What is git and why do we use it?
2. Git installation
3. Repositories
    - Define repos and explain why we use them
    - Have students clone the git training repo
4. Branches
    - Explain what a branch is (Add plenty of diagrams as well)
    - Have students branch off main
5. Commits
    - Explain what commits are and syntax for pushing/pulling changes
    - Excercise:
        1. Make a new file and write something
        2. Run status
        3. Stage the file
        4. Run status
        5. Commit changes (Maybe something on proper commit messages)
        6. Push to remote repo
        7. Have them check the training repo on their branch
        8. Make them write something else to a file, stage it, and commit it
        9. Make them write a third thing to a file, stage it, and commit it
    - Also maybe add an excercise on deleting commits, unstaging stuff, etc
    - Using git log
6. Tagging commits
    - What tagging is, why we use it
    - Tagging syntax (Tagging commits, retagging using -f, pushing tags, checkout tags, etc)
    - Have the student tag a prior commit
7. Cherry picking
    - What it is, how to do it
    - Have students branch from a previous commit
    - Have them make a new commit (Making a new file or something)
    - Have them cherry pick it to their other branch
8. Squashing
    - Why squashing commits is used and how to squash
    - Have them squash their file commits in step 5 into 1 commit (Something like "Add info about me")
9. Merges
    - Go over merging and merge conflicts
    - Not really sure what to do as an example. Maybe they could use their secondary branch to cause a conflict and then fix that?
9. PRs
    - Explain what PRs are
    - Have them PR their branch when they're done with the training
10. Practical logistics
    - TBD

Other files:
- Test cheat sheet
- Readme introduction
