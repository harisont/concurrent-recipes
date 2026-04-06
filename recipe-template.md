---
title: The title of the recipe
tags: a list of comma-separated tags (optional)
threads: an integer indicating how much the recipe can be parallelized
time: an integer indicating the approximate time needed to follow the recipe in minutes
---

Optional intro text, hidden by default, displayed when the user enables the `--verbose` mode. 
Images, including their alt text, are also hidden unless verbose mode is on.
Two main sections (Ingredients and Steps) are mandatory; Equipment is optional.
Both subsections and other main sections are allowed, but the latter are discouraged as we might decide to hide them by default too.

## Ingredients
- ingredient 1
- ingredient 2
- ...
- ingredient n

## Equipment
- item 1
- item 2
- ...
- item n

## Steps
1. step 1
2. - step 2, person 1
   - 1. step 2, person 2 (substep 1)
     2. step 2, person 2 (substep 2)
3. ...