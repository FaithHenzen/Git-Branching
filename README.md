# Git-Branching

Learning Git Branching.

## Define terms

- Branch

It is the creating of different branches of the project at the same time to enable programmers to work on the code colaboratively  without affecting the main code and once the changes are made the branches are mergerd back to the main branch.
 
 BENEFITS

- 1 Isolation
- 2 Parallel Development
Allows colaborative coding

## How to create a branch using Git commands

  1 .Creating a branch
'bash

     git branch "branchname"


2. Switching between branches
' bash

     git switch "branchname"
     
     git checkout "branchname" 
'
     Dirrectly switching to a new branch
'bash

     git checkout -b "branchname"

3 .Merging
'bash

     git merge "sourcebranch"

4.Conflicts and errors

'bash

     git mergetool
5.List all branches

6.A ist of extra commands
'bash

    git branch
'bash

    git branch-v

'bash

     git status '

List merged commits
'bash

    git branch--merged
List unmerged commits
'bash

    git branch--no-merged
    
#### Bonus Command
'''  code
<h1>git log</h1>
'''