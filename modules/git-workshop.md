[![Kottans-Frontend][badge-kottans]][kottans-git]
[![MIT Licensed][badge-mit]][license]
![Entry level: beginner][badge-beginner]

# Git workshop

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [Why to participate?](#why-to-participate)
- [Workshop targets](#workshop-targets)
- [What to know to enroll?](#what-to-know-to-enroll)
- [Having workspace properly set up](#having-workspace-properly-set-up)
- [How to enroll?](#how-to-enroll)
- [Model workshop plan](#model-workshop-plan)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->
<!-- generated with [DocToc](https://github.com/thlorenz/doctoc) -->

## Why to participate?

The workshop is held offline and aimed at putting hands on
practical work to support participants' learnings.

Participants are required to have learned Linux CLI and Git skills 
from this course modules to enroll in the workshop.

## Workshop targets

Get a hands-on experience with:
 - using proper git workflow
 - submitting code changes by means of pull requests
 - conducting code review
 - approving changes and requesting changes
 - resolving code conflicts
 
Secondary skills:
 - updating feature branches from remotes and base branches
 - mastering rebasing and back-up branches
 - squashing commits

## What to know to enroll?

 - Linux CLI basics: navigating across file system, files manipulations,
   using command history
 - Basic MarkDown syntax
 - Git basics: `init, clone, add, commit, checkout, branch, merge, push, pull`
 - Git collaboration essentials: working with remotes, forking,
   working with pull requests

Feel free refreshing any knowledge of the above by revisiting the course 
modules.

## Having workspace properly set up

1. CLI editor (nano is a good choice, however any you feel comfortable with
   will do)
1. Git Credentials Manager installed and set up 
   (to save time when pushing changes)
1. Command prompt tuned up for use with Git
1. Git CLI completion setup
1. Global `.gitignore` in your user home directory
   (with at least IDE specific directories listed)

Some of the items above are covered by the Udacity Version Control with Git
course from [Git Basics module](./git-basics.md):
[**Mac/Linux Setup**](https://classroom.udacity.com/courses/ud123/lessons/1b369991-f1ca-4d6a-ba8f-e8318d76322f/concepts/63a6f935-dea7-43c2-aaa3-61deea5070c8),
[**Windows Setup**](https://classroom.udacity.com/courses/ud123/lessons/1b369991-f1ca-4d6a-ba8f-e8318d76322f/concepts/8a5af628-7a18-49cf-bbc8-02691762f862).

[**Developer's Environment: Git**](https://github.com/OleksiyRudenko/dev-env-git)
project offers a comprehensive guidance to setting up comfortable
developer's Git environment.

## How to enroll?

TBD

## Model workshop plan

**Preamble**
1. Get introduced to each other
1. Workshop targets
1. Check dev environment
1. Agree on Git flow conventions, branch naming and commit messaging
1. Form sub-teams for shorter mutual code review cycle

**Exercise 1.** Mess
1. Each contributor adds changes to a personalized file 
   via personalized branch and opens a PR
1. PRs merged into base branch
1. Observe history mess

**Exercise 2.** Easy and Nice
1. Each contributor adds changes to personalized files 
   via personalized branch (three times: to file 1, to file 2,
   to file 1 again) 
1. Leader introduces changes
1. Each contributor in a round-robin:
   - updates their branch using rebase strategy
   - reorders and squashes their own commits
   - opens a PR
   - waits for a peer to request changes
   - updates per request
   - waits for a peer to approve changes
   - gets PR merge-squashed onto the base branch

**Exercise 3.** Oh, no! My code is better
1. Each contributor adds changes to a shared file 
   via personalized branch
1. Leader introduces changes to the shared file
1. Each contributor in a round-robin:
   - updates their branch using rebase strategy
   - resolves a conflict
   - opens a PR
   - waits for a peer to approve changes
   - gets PR merge-squashed onto the base branch

---

[Course contents](../README.md)

[badge-kottans]: https://img.shields.io/badge/%3D(%5E.%5E)%3D-git-yellow.svg
[kottans-git]: https://github.com/kottans/git-course

[badge-mit]: https://img.shields.io/badge/License-MIT-blue.svg
[license]: https://github.com/kottans/git-course/blob/master/LICENSE.md

[badge-beginner]: https://img.shields.io/badge/Entry%20level-beginner-brightgreen.svg
