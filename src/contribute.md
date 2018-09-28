# How to Contribute:


We use the pull-request model, see [GitHub's help on pull-request](https://help.github.com/articles/using-pull-requests).

In brief, you will:

* on GitHub, find and fork the source repository;
* on your computer, clone your fork repository,
* commit your changes in a new branch;
* push your branch and submit a pull-request for it;
* go through the review process until your pull-request is merged; and

_Please note there is no need to ask permission to work on an issue. You should check for pull requests linked to an issue you are addressing; if there are none, then assume nobody has done anything._

_Begin to fix the problem, test, make your commits, push your commits, then make a pull request. Mention an issue number in the pull request, but not the commit message. These practices allow for sanity and orderliness for revieweres_

# Projects:


All of our active repositories can be found on our [GitHub O.S.C.A`organization](https://github.com/oscommunityafrica).


### Checklist - anyone

* [ ] make a fork and clone it,

* [ ] confirm if what you want to change is already present in any other branches or forks,

* [ ] make and test your changes,

* [ ] if your changes add a new feature or will affect users; update the README.md file

* [ ] make a branch, push your commits, and a pull request, see [Workflow](##workflow) below.

### Checklist - maintainer

* [ ] look for commits _after_ any of these, in either;

    * [ ] master branch of repository at O.S.C.A,
    * [ ] any other branches,
    * [ ] any other forks,

* [ ] review and merge all pull requests,

* [ ] apply all desired commits, make pull requests if review is needed,

* [ ] update the README.md file if necessary,

## Workflow


### Open an Issue

We track issues in the GitHub Issues tab of repositories.

An improvement to any of the projects may start with an issue discussion, to build consensus and ensure that work isn't wasted.  An issue may be avoided for fixing bugs that are obvious to everyone or part of a project.

### Forking

You should first fork a repository on GitHub. This step is needed only once.
See [complete help in GitHub](https://help.github.com/articles/fork-a-repo).

### Cloning

You should clone your fork. This step is needed only once.
Using [sugar](https://github.com/oscommunityafrica/docs) as example;

```
git clone git@github.com:YOUR-NAME/sugar.git
cd docs
git remote add upstream https://github.com/oscommunityafrica.git
git fetch upstream
```

### Branching

Create a branch per set of changes; e.g. to fix a problem or add a feature;

```
git checkout -b BRANCH-NAME
```

Your BRANCH-NAME can be anything, other than master.  The scope is your forked repository.  The branch name will be shown on pull-requests.

### Making commits

Change files, and commit.  Commit messages are kept by git, and are used later when problems are being solved.  When writing a commit message;

1. start with a one line summary of the change;
2. leave a blank line after the summary;
3. explain the problem that is solved, unless the summary makes it obvious;
4. when the problem was introduced by a previous commit, mention the hash;
5. when the problem is in an issue or ticket, add "Fixes #34";
6. avoid mentioning GitHub or other pull-requests, as these are not kept in git;
7. avoid mentioning any tasks or irrelevant words ; use pull-request comments instead; and
8. make use of british english in spellings imperative mood

Make one or more commits and push the branch to your repository;

```
git push origin BRANCH-NAME
```

### Sending a pull-request

Send a pull-request for your branch.
Navigate to your repository page in GitHub, switch to the branch you made, and then press the **Pull Request** button.

When writing a pull-request message;

1. if there is only one commit, begin with the GitHub default of the commit message, otherwise write a summary of the series of commits;
2. link to any relevant pull-requests, issues, or tickets; and

A review will happen in the pull-request, and a reviewer will either;

1. merge, squash, or rebase your commits;
2. merge your commits with their own changes;
3. ask you to make changes; or
4. close and reject your pull-request giving reasons.

When they ask you for changes, you may have to change both files, commits or commit messages.

When squashing commits to different files, use interactive rebase.

```
git rebase -i master
```

After resolving any conflicts, push the changes to the same branch;

```
git push --force origin
```

Then respond on the pull-request.

### Keep your pull-request up to date

When there has been upstream commits while your pull-request was open, you should rebase your pull-request;

```
git pull --rebase upstream
```

Then push the changes to the same branch;

```
git push --force origin
```

The pull-request will be updated.

### Keep your fork up to date

When there has been upstream commits since your fork was made, you should bring these into your fork:

```
git checkout master
git pull upstream
git checkout BRANCH-NAME
```

### Review

We encourage testing before merging a pull-request.

So instead of merging directly with the "merge" button on GitHub, we may do a local merge, then test, then push.

See [GitHub help on merging a pull-request](https://help.github.com/articles/merging-a-pull-request).

The GitHub page for the pull-request will provide you the right commands to do the local merge, similar to the following.

Get the changes from that branch to a new local branch:

```
git checkout -b SOME-USER-topic1 master
git pull https://github.com/SOME-USER/doc.git topic1
```

Test! If everything is fine, merge:

```
git checkout master
git rebase SOME-USER-topic1
git push origin master
```

### Close Issue

Once your pull-request is merged, you should close any issue or ticket.  GitHub issues named as "Fixes" in a commit message may be automatically closed.

Be sure to thank everyone who helped you out along the way.

# Guide for Reviewers

### Goals

The Goal(s) for every review is to;

* detect trivial mistakes,

* maintain consistent and good code quality,

* reproduce test results, (especially for critical repositories),

* maintain a useful git commit history for use by git bisect, and developers who read it,

* maintain other records, such as issues, tickets, and documentation,

* not waste the time of the contributor, by doing anything trivial that otherwise the contributor might have to do.

### Checklist

* [ ] does the change have consensus of the community, see also our [code of conduct](src/OSCA Code of Conduct.md) (if a reviewer is in doubt, seek opinions by @mentioning people),

* [ ] does the commit message explain the summary, problem, and solution, so that it can be used in future analysis, see also [making commits](#making-commits) (if a reviewer can fix it by squash or manual rebase, do so),

* [ ] does the commit message reference any issue (if a reviewer can fix it by squash or manual rebase, do so),

* [ ] are the number of commits excessive for future analysis, (a reviewer may squash or rebase if necessary),

* [ ] is the changed code consistent in style with the existing code

Frequently Asked Questions
--------------------------

### I've used the GitHub editor, how can I rebase or amend commits?

Make a local clone of your GitHub repository, use `git commit --amend` or the other advanced CLI features, then `git push` back to GitHub.

### Error 403 on `git push`

You have Most likely cloned someone else's repository, and you should instead fork their repository, clone your own repository, make your changes, then push.
