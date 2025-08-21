---
title: "Edit EDAM with git"
nav_order: 1
permalink: /docs/13-git_add_concept/
classes: wide
sidebar:
  nav: "documentation_sidebar"
---

## Add new concept with git

(assuming basic knowledge of git and user having created a fork, cf section 12 EDAM git repo)

(WIP)

1. Check fork is synchronised with edamontology main 

> git switch main
> git fetch upstream

2.Create and switch to new branch + double check you are in new branch

> git checkout -b <name_branch>

> git branch

3. Make changes locally in file EDAM_dev.owl

- Add concept (to do add template rdf)
- Edit IDs accordingly (edam:next_id)
- Edit timestamps (oboLegacy:date, owl:versionIRI)
- Edit author (oboInOwl:savedBy)

4. Commit changes and revise commit. Note: use conventions for commit message (template and or links)

> git commit EDAM_dev.owl
“
Add new concept <label> in <class> 
“

> git log

5. Push changes from new branch to EDAM main repository

> git push --set-upstream origin <name_branch> 

6. Check fork on github (switch from “main” to new branch in drop down menu) (screencap)

Make sure there are no commits behind

7. Create pull request (screencap)

- Assign oneself
- Add reviewer(s)
- Add label (“concept/term addition”)
- Add milestone (EDAM next release number)

8. Synchronise fork after PR is merged 

- Switch to main
- Delete branch

> git switch main

> git branch -d <name_branch> 