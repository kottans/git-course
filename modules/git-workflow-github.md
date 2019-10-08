[![Kottans-Frontend][badge-kottans]][kottans-git]
[![MIT Licensed][badge-mit]][license]
![Entry level: beginner][badge-beginner]

# Git workflow and GitHub

This module looks big. Actually it is more about concepts
and tasks per se are tiny.

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
## Table of Contents

- [A. Why mastering this?](#a-why-mastering-this)
- [B. Intro to problem solving](#b-intro-to-problem-solving)
  - [B1. Problem identification](#b1-problem-identification)
  - [B2. Solution suggestion](#b2-solution-suggestion)
  - [B3. Solution alignment and approval](#b3-solution-alignment-and-approval)
  - [B4. Putting solution into life](#b4-putting-solution-into-life)
- [C. Targets](#c-targets)
- [D. Learn and Do](#d-learn-and-do)
  - [D1. Issues](#d1-issues)
  - [D2. Discussion](#d2-discussion)
  - [D3. Forking](#d3-forking)
  - [D4. Pull request](#d4-pull-request)
  - [D5. Code review](#d5-code-review)
  - [D6. Code conflict resolution](#d6-code-conflict-resolution)
  - [D7. Approve and Merge Pull Request](#d7-approve-and-merge-pull-request)
  - [D8. Draft pull request](#d8-draft-pull-request)
- [E. When completed](#e-when-completed)
- [F. Extras](#f-extras)
  - [F1. Gist](#f1-gist)
- [When completed](#when-completed)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->
<!-- generated with [DocToc](https://github.com/thlorenz/doctoc) -->

## A. Why mastering this?

Git is not only about storing versioned code but is also
about communication. There are some communication patterns
to follow that will make interaction with your peers and
superiors easier and better structured, i.e. more efficient.

The collaboration flow highlighted in this module comprises:
- keep you local code base in sync with shared remote
- work in a topic branch
- open a pull request to submit code changes
- have code reviewed, change requests served and/or approved
- merge into development or master branch

## B. Intro to problem solving

A problem solving workflow, in general, comprises:
1. Problem identification
1. Solution suggestion
1. Solution alignment and approval
1. Putting solution into life

In software development the above maps as follows:

### B1. Problem identification

A problem can be e.g.:
- lack of a feature
- a bug (whether it is a logical or a functional bug, or a typo)
- a need of improvement

When a problem is identified it should be reported as an issue
in relevant repo context.

Issue details can contain Steps to Reproduce and environment
details (bug),
suggestions on the solution (feature or improvement request).

### B2. Solution suggestion

Once a problem is documented as an issue it can be assigned
to someone. Issue reporter can assign himself or herself,
or a team lead can assign the issue to someone from the team.

Solution suggestion itself is a commit of code (or text) that
solves the problem (normally in a feature branch) submitted
with a Pull Request (Merge Rerquest in other cloud VCS).

### B3. Solution alignment and approval

Solution alignment is a process where stakeholders or peers,
or supervisors have an opportunity to conduct code review 
(cross-check the solution for correctness or safety,
or ability to achieve the solution goal).

Depending on conventions in a team, a Pull Request author may
assign a team lead or peers to review the PR. Alternatively peers
may assign themselves to review the PR as per their capacity.
The team lead may re-assign the PR to someone else.

Changes can be requested in the course of the Pull Request review.

Solution approval is a process where key stakeholders or
decision makers confirm that the solution is appropriate.

Normally, review from at least two peers is required. This
also depends on the team conventions. 

### B4. Putting solution into life

Putting solution into life means it becomes a part
of the code base by merging into (or rebasing onto) `master`
or other production streamline branch.

This is normally done by one of reviewers or by a team lead
once there are no non-resolved change requests and
required number of approvals (e.g. two) are obtained.

## C. Targets

GitHub offers Issues and Pull Request mechanics.

Skills to earn, improve or refresh:
 - Issues
   - open an issue
   - assign executor
   - close an issue manually
   - close an issue with a code commit
 - Pull Requests
   - open a Pull Request
   - assign reviewers
   - conduct code review
   - request changes
   - approve PR
   - merge PR into `master`
   - draft pull requests to discuss incomplete solutions
 - Gists - code snippets not worth their own repo

To feel safe we shall play around with text. Actually,
MarkDown is a type of code, just like HTML,
as it gets interpreted to render a nice document view.

## D. Learn and Do

### D1. Issues

Note that it is good to start an issue title with a proper verb
(like we do for commits):
 - `Fix` for a bug
 - `Add` for enhancement or a new feature
 - `Change` for enhancement
 
Just imagine that someone fixing the issue will create a commit with
the very same message at your issue title. It will establish a strong
binding between the issue and commit that resolves it.

**Read**

- [Creating an issue](https://help.github.com/en/articles/creating-an-issue)
- [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)

**Do**

_Option 1._ You might have noted something not so easy to master or
comprehend in the past modules. This might be a good source of an idea
to create an issue on.
Let's take this as a need for improvement.

_Option 2._ The course materials may contain a broken link, a typo in
the text, something like http://domain.com/a-very-long-url instead of
nicely formatted [link](./#). Let's take this for a bug.

_Option 3._ Course is really a Work In Progress and misses many modules
to be populated with educational content. Let's take this as a lack of
a feature.

_Option 4._ Any other bug, need of improvement or lack of a feature.

Cannot invent a problem? No problem. Check this 
[document full of typos](./github-typos.md).
Or just ask your peers for support and ideas.

Simple issues (like typos) can be resolved with a single commit and
without a discussion. But let's learn on a simple case to be ready for
more complicated ones.

The **task is** to
- open (create) an issue [here](https://github.com/kottans/git-course/issues/)
- give it an informative title
- describe the issue
- add a label (e.g. `bug` or `enhancement`)
- submit

Check this [issue #1](https://github.com/kottans/git-course/issues/1)
for example.

And remember, MarkDown is here to make your issue description easier
to read.

### D2. Discussion

**Do**

- Pick an issue that cannot be resolved easily as it requires
  lots of information (e.g. educational materials) or obviously
  incomplete (a suggestion to add a module).
- Add a comment suggesting how to resolve or complete the issue

Check this [issue #1](https://github.com/kottans/git-course/issues/1)
for an example.

You're done.

### D3. Forking

You make a fork of a repo when you
- do not have rights to push directly to a repo
- want to work on your own for a longer time
  without burdening a repo with incomplete code
- want to develop a Free Open Source Software
  in a way that doesn't match the project's
  official roadmap
  (make sure project's license allows you doing so)
  
What is nice with forks is that you can create a Pull Request
into original repo from your fork's branch!

**NB!** Cloning a repo and just pushing it up to your space
doesn't create a fork binding and will not enable cross-repositorial
pull requests.

**Read**

- [Forking projects](https://guides.github.com/activities/forking/)
- [Fork a repo](https://help.github.com/en/articles/fork-a-repo) - freely experiment with changes without affecting the original project
- [Sync a repo](https://help.github.com/en/articles/syncing-a-fork) - keep a fork of the repository up-to-date with the upstream repository

**Do**

[Fork a repo practice](https://help.github.com/en/articles/fork-a-repo)

You need this skill in order to complete the following task.

### D4. Pull request

Pull request is a device to propose code changes (consider `.md` file
is some code as well, like HTML), have a spare pair of eyes to look
at (doing a code review), and approve a good solution.

**Read**

- [Creating a pull request](https://help.github.com/en/articles/creating-a-pull-request)
- [Pull Request Tutorial](https://yangsu.github.io/pull-request-tutorial/)

**Do**

- Choose an issue to resolve:
  - Pick an issue that is good to be resolved or implemented (a bug,
    a feature or an enhancement) and has no an Assignee (that means
    no one takes care of this issue yet)
  - Assign yourself, so others know that someone works with the issue
- Fork the repo into your own workspace on GitHub
- Make changes in the code:
  - Clone (if not yet) with `git clone...` or update your local clone
    `master` of the forked repo (`git checkout master && git pull`)
  - **Create a feature branch** with `git checkout -b <new-branch-name>`
    (branch name would give a general idea of the code associated with it)
  - Change or add some code and commit
  - Push your branch to remote with `git push...`
- Open a Pull Request:
  - Navigate to the forked repo on GitHub
  - Open a pull request
  - Give your PR short yet descriptive title, so from pull requests list
    one could see what to expect inside a particular PR
  - Describe the targets in the PR body so that readers can understand
    in more details what the PR is about
  - If your PR resolves an issue just add `Resolves #3` somewhere 
    in the comment (`3`
    is a number of an issue you can see beside its title). GitHub will
    bind your PR to that issue and the issue will get closed
    (as resolved) once your PR is merged.
- Draw attention
  - PR created from a fork is bound to the original repo by GitHub,
    so navigate to the original repo, Pull Requests and open a PR
    you've opened
  - There is a PR management section on the right side of the PR.
    Click **Reviewers** and assign two or three of your peers.

**Alternative**

Send a pull-request to [Kottans/mock-repo][mock-repo] proposing a change.
It could be anything, really. If you have found a typo in `README.md` -
great!
Take care to give your PR a meaningful name and description.
Please, do not suggest changes via GitHub Web UI, the target
is to emulate code contribution flow using `branch-commit-push`
techniques.

_Please note, that your PR may not be reviewed quickly._

**Something went wrong?**

- Irrelevant commits somehow became part of the PR?
- Forgot to create a feature branch?

Seek for the help among your peers (e.g. in a chat).
Also you may find
[this guide](https://gist.github.com/OleksiyRudenko/8b3ddb664308de0634b53c525e551d8b)
helpful when facing irrelevant commits problem.

Pull Requests are contributions. Many projects contain contribution
guidelines, many guidelines are quite applicable across projects.
Whenever you see `CONTRIBUTING.md` it is worth reading before you
start contribution to a project.

You may find something useful or interesting in other projects'
contribution guidelines.
Check this [example 1](https://github.com/kottans/frontend/blob/master/CONTRIBUTING.md),
and this [example 2](https://github.com/kottans/frontend-2019-p2p/blob/master/CONTRIBUTING.md).

### D5. Code review

It is a good practice to conduct a code review to make sure
a PR introduces useful, bugless :smirk: code.

By convention, approvals from two code reviewers is
required to approve a PR.

Code review can be as short as `LGTM` (Looks Good To Me) with an approval
or a series of comments to the code with a Change Request.

**Read**

- [Code Review Guidelines](https://github.com/kottans/frontend-2019-p2p/blob/master/code-review-guidelines.md)
- [PR Code Review Phrase Book](https://gist.github.com/OleksiyRudenko/e6f573d7aca2cc854ccce6087cfe7138)
- [About pull requests review @ GitHub](https://help.github.com/en/articles/about-pull-request-reviews)

**Do**

- Check [pull requests](https://github.com/kottans/git-course/pulls) and
  find a pull request you are assigned to conducts a code review to
  or a PR with code reviewers assigned. You may assign yourserlf
  as a code reviewer
- Look through PR. There shouldn't be anything too complicated
- Conduct a code review
- It is good to add a couple of positive comments in the code
  to encourage the author before you just post `LGTM` and approve
- Feel free requesting changes (e.g. fix a typo or formatting, add a
  link etc)

### D6. Code conflict resolution

At any stage of PR the author may face a code conflict.
GitHub will warn you. This section is intended
to make you well prepared. No panics!

**Read**

- [Resolving a merge conflict using the command line](https://help.github.com/en/articles/resolving-a-merge-conflict-using-the-command-line)
- [Resolving a merge conflict on GitHub](https://help.github.com/en/articles/resolving-a-merge-conflict-on-github)

**NB!** Resolving a conflict using command line is a preferred method
in many cases.

**Do**

- Install [GitHub lab tool](https://lab.github.com/install?org=githubtraining&course=managing-merge-conflicts) and watch
  a short intro video when offered to Join your first course
- Pass [Managing merge conflicts](https://lab.github.com/githubtraining/managing-merge-conflicts) -
  a 10 steps tutorial

### D7. Approve and Merge Pull Request

Once a PR is approved (e.g. by 2 code reviewers) the code proposal
can be merged into master.

**Read**

[About merge methods on GitHub](https://help.github.com/en/articles/about-merge-methods-on-github)

**Do**

GitHub offers three merging strategies:
- Create a merge commit
- Squash and merge
- Rebase and merge

Opt for squash or rebase as these keep the git history linear.

- Choose **Squash and merge** or **Rebase and merge** option instead of
  **Merge pull request**
- You will be offered a commit message draft. Edit it so clearly
  describes the changes introduced with PR. In the next input field
  (_Add an optional extended description_ or suggested list of changes) 
  make sure that the last line contains words e.g.
  `Resolves #3` to make GitHub bind this PR with a relevant issue by
  issue number
- Click **Confirm...*
- Once merged click a button to delete current branch - you do not need
  it anymore

You are done! 

**What if a PR should be closed without merge?**

If you decide just to close a PR, i.e. reject it or cancel,
you can do it with **Close pull request** button.

It is important to give a reason for your peers and
future yourself. Reason shouldn't be extensive, just
a couple of clear words. Check
[this](https://github.com/kottans/git-course/pull/2#issuecomment-526934953)
out for example.

### D8. Draft pull request

Draft Pull Requests are the same as normal Pull Requests.
The only difference is that a _draft_ Pull Request cannot be merged into
the repo codebase until it is finalized and ready to become a real
code proposal.

Draft Pull Requests are good to open discussion on incomplete
code, e.g. when you get stuck and need help or an advice.

**Read**

[Introducing Draft Pull Requests](https://github.blog/2019-02-14-introducing-draft-pull-requests/)

## E. When completed

You did a lot and greatly improved your git and collaboration skills!

When done let others know you have passed this module.

This lets other know your progress and probably someone
will ask you for some help in this module.

Where to communicate? In a chat you come here from :)

Now you are ready to efficiently collaborate with your teammates
in a real project and contribute to Open Source Projects.
Tell others that you are eager to get involved
into any.

:gift: On GitHub you get subscribed for notifications when
e.g. a new repo is created in your organization.
You can unsubscribe from notifications on selected repos
[here](https://github.com/watching) or even from
[a particular organization](https://gist.github.com/OleksiyRudenko/00be70f0915aea7affb18ab8c6e7c8c8).
This would help to see only notifications you want.

Meanwhile you may want to become a 
[Git Ninja](./git-ninja.md).

## F. Extras

- [Creating a permanent link to a code snippet](https://help.github.com/en/articles/creating-a-permanent-link-to-a-code-snippet)
  (e.g. for cross-referencing in an issue on related topic)
- [Opening an issue from code](https://help.github.com/en/articles/opening-an-issue-from-code)
  (e.g. for a bug report)
- [GitHub Learning Lab - practical courses](https://lab.github.com/courses)

### F1. Gist

Gist is a tiny repo, and normally used to keep simple, often
single file code snippets or docs, that do not deserve to be
a project and need no much collaboration via e.g. Pull Requests.

**Read**

- [About gists](https://help.github.com/en/articles/about-gists)
- [Creating gists](https://help.github.com/en/articles/creating-gists)

**Do**

- Navigate to [gists](https://gist.github.com/)
- Create a simple gist named **Test** with a single `test.md` file in it
- Type a couple of MarkDown lines and save
- You may also delete this test gist

## When completed

Proceed to [Git workshop](./git-workshop.md)

---

[Course contents](../README.md)

[badge-kottans]: https://img.shields.io/badge/%3D(%5E.%5E)%3D-git-yellow.svg
[kottans-git]: https://github.com/kottans/git-course
[mock-repo]: https://github.com/kottans/mock-repo

[badge-mit]: https://img.shields.io/badge/License-MIT-blue.svg
[license]: https://github.com/kottans/git-course/blob/master/LICENSE.md

[badge-beginner]: https://img.shields.io/badge/Entry%20level-beginner-brightgreen.svg
