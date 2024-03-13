---
tags:
  - earn
  - fortress
title: Fortress Mma Score
product: null
date: 2023-10-04
description: null
authors:
  - hnh
menu: earn
due_date: null
status: Done
PICs:
  - nam
completion_date: null
bounty: 120
hide_frontmatter: true
type: earn
---

1. Update fortress database

Create a new table `employee_mma_scores`

including (but not limited):

- employee_id
- mastery_score
- autonomy_score
- meaning_score
- rated_at

2. Create a Discord command

`?profile @member` (smod or above perm)

data: latest mma score, basic info, project info

design: add later (hnh)

2.1 Specific Channel Permission

Create a scoped channel, same as scoped role permission

this command only run in defined channels

1. Discord command to export a template csv

`?mma template` (smod or above perm)

result a `mma-template.csv` file follows format as below:

header: full_name, mastery, meaning, autonomy

template data must includes all active employee from `employees` table

1. Fortress function to import mma csv

Button on website (like Create invoice button) to import a csv

read data from csv file and input to `employee_mma_scores` from 1)

Notes:

- Create new Permission Rule for 2,3,4 in the backend
- Please release fortress 1 by 1
