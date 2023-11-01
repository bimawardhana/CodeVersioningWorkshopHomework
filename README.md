# CodeVersioningWorkshopHomework

Hello. This is Bima (@bimawardhana) from DWE team. 

## Summary of Topics Covered

### Version Control

- version controls by definition: trying to capture snapshots (or like checkpoints in games) of files or directories
- being done manually: 
    - possible
    - e.g. create different files for each snapshot
    - but it is painful because there's a lot of manualy copy 
    - also not scalable for cases where the amount of file is huge
- git makes it easier to do version control
    - `git add`: choosing file to be included in the "snapshot"
    - `git commit`: creating the "snapshot"

### Hub of Git

- idea: storing repo somewhere remote that could be accessed by many people (collaborators)
- solution to using git for teams (many collaborators)
- Github is one of the example
- how it works? generally:
    - collaborators clone remote repo to local
    - make changes in local 
        - create branch. see [assignments/branching/summary.txt](https://github.com/bimawardhana/CodeVersioningWorkshopHomework/blob/main/assignments/branching/summary.txt)
        - do some commits
    - maybe pull from remote to update local repo
    - push to remote
    - request PR (for review before merge)
    - merge branch see [assignments/merging/summary.txt](https://github.com/bimawardhana/CodeVersioningWorkshopHomework/blob/main/assignments/merging/summary.txt)

## Challenge & Lesson Learnt

- Personal Github is not enterprise so it's not possible to enforce to protect `main` branch.
