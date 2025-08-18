---
title: "Edit EDAM with git"
nav_order: 1
permalink: /docs/04-git/
classes: wide
sidebar:
  nav: "documentation_sidebar"
---

### Adding a new concept

1. Fork edamontology repository

2. Synchronise fork with edamontology main 

3. Create and switch to new branch 

> git checkout -b New_concept_xxx

> git branch

4. Make changes locally in file EDAM_dev.owl

* Add concept
* Edit IDs accordingly (edam:next_id)
* Edit timestamps (oboLegacy:date, owl:versionIRI)
* Edit author (oboInOwl:savedBy)

5. Commit changes and revise commit (use conventions + for commit message)

> git commit EDAM_dev.owl

> git log

6. Submit changes

> git push --set-upstream origin New_concept_xxx 

> git switch main

7. Create pull request and assign reviewer(s)

8. Synchronise fork after PR is merged, switch to main, delete branch
