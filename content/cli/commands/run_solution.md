---
title: Run Solution
linktitle: run solution
description: run solution from public template

categories: []
keywords: []

menu:
  docs:
    parent: "commands"
    weight: 5

weight: 2

draft: false
---

### run solution

**Description**:

run solution from public template

**Example**:

chkit run solution [$PUBLIC_SOLUTION] [--env=KEY1:VALUE1,KEY2:VALUE2] [--file $FILENAME] [--force]

**Flags**:

| Short | Name | Usage | Default value |
| ----- | ---- | ----- | ------------- |
|  | branch | solution git repo branch, optional | master |
|  | env | solution environment variables, optional |  |
|  | file | file with solution data, .yaml or .json, stdin if '-', optional |  |
| -f | force | create solution without confirmation, optional | false |
|  | name | solution name, optional, autogenerated if void |  |


