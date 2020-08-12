# README

**Welcome to Le Wagon's 'Collaborate with Git' Workshop!**

This workshop will quickly cover the basics of git but then go a bit further to explore what it is like to work on a team and manage a project with collaboration.

The All About Git repo was created just for this workshop and will continue as an open-source project for collaborators to use as practice, but also in the hopes of building a Git wiki that can be published and accessed by anyone. So please, contribute, contribute, contribute, but with the foresight of building a well-maintained and reliable Git wiki.

**What does this project entail?**

-   Overview of Git basics
-   Advanced commands on the basicz
-   Learning to colaborate effectively

**Configure your Environment**
-   Open up your terminal or command prompt
-   Download git by following the directions here based on your operating system (Mac, Linux, PC). The easiest way is to use the installers: https://www.atlassian.com/git/tutorials/install-git
-   Make sure you have a text editor downloaded so you can interact with the code (Sublime, VS Code, Atom, Brackets, etc.). You can download Sublime here: https://www.sublimetext.com/3

**Contributor TODO**

-   Open issues
-   Improve/Edit/Add content
-   Create PRs
-   Make any requested changes
-   Add your name to the Contributors list!

This project is hosted on GitHub Pages at: https://rmklaus12.github.io/all-about-git/

In the root directory, there is a HTML template file for you to use to get a jump start when adding a new page to the site.

Make your changes in your editor of choice, and push to GitHub as instructed. The instructors will approve your PRs, merge with master, and changes are automatically deployed to GitHub Pages. You can refresh that site at any time to see changes.

**Get the repo**
Start your contributing journey with us by forking this repo using the Fork button in the top-right corner of this screen. You should then be able to use git clone to copy your fork onto your local machine.

```bash
    git clone https://github.com/YOUR_GITHUB_USERNAME_HERE/all-about-git
```

Jump into your new local copy of All About Git:

```bash
    cd all-about-git
```

And then add an `upstream` remote that points to the main repo:

```bash
    git remote add upstream https://github.com/rmklaus12/all-about-git
```

Fetch the latest version of `master` from `upstream` (ie. the main repo):

```bash
    git fetch upstream master
```

**Issues**

-   Opening an issue

    -   https://docs.github.com/en/github/managing-your-work-on-github/creating-an-issue
    -   Issues should be opened with a problem or need is discovered. This can be a bug (faulty code) or a requested enhancement.
    -   Issues can be assigned labels (see below) to help identify and/or classify them.

-   Assigning an issue

    -   https://docs.github.com/en/github/managing-your-work-on-github/assigning-issues-and-pull-requests-to-other-github-users
    -   You may self-assign issues that you would like to tackle

-   Closing issues
    -   Issues will be closed by the senior devs (aka the instructors)

| Label            | Description                                        |
| :--------------- | :------------------------------------------------- |
| good first issue | A great place to start for new contributors!       |
| HTML/CSS         | Working knowledge of HTML/CSS required             |
| content          | Add content to existing page - no coding necessary |
| bug              | Something isn't working                            |
| enhancement      | New feature or request                             |

**Making changes**

Make your changes on your computer using your favourite code editor.

Once you begin work on a particular issue, you should create a feature branch to make your changes. This keeps your master branch clean and also allows you to work on multiple issues at the same time and prevent any conflicts.

```bash
    git branch <your-branch-name> #creates a new branch
    git commit -m "Add a concise commit message describing your change here"
```

Once you've made your changes, you can commit.

```bash
    git add .
    git commit -m "Add a concise commit message describing your change here"
```

Push your changes to a branch on your fork:

```bash
    git push origin branch-name-here
```

**Commits**

_Keep your commit history clean, tidy and up-to-date_

Your commit history should contain only commits that are relevant to the change you are making. If you find that the list of commits for your PR contains commits that you did not make, then it is possible that you have accidentally merged something into you branch that you shouldn't have. Using `git rebase -i` to clean up your commit history and keep up to date.

_Commit messages should..._

-   be as short as possible, while providing enough detail to understand what is happening and why the change is being made
-   begin with a capital letter, and should not contain a full stop
-   ideally begin with an imperative verb "Add...", "Update...", "Fix...", "Remove..."
-   not be overly simplified or not explanatory (eg. `Emergency save`, or `Debug enterprise controller`, or `Tidy up`)

**Pull Requests**

_Making a great PR_

Most pull requests are solving one issue. It's useful to include the issue number in the pull request's name, for example `3727-add-content-aboutpage`.

_Provide an explanation of the problem you are solving_

When you create a PR, you have the opportunity to explain the changes you have made to the codebase, and the more detail you provide, the better. Mention the other issues in the repo that your PR is related to. Someone needs to review your contribution before is merged into the code base. Having lots of information about what they are looking at makes the job of a reviewer much easier, and means that feedback is likely to be faster. That means we can get your change merged as quickly as possible.

If you are the only one working on your PR, and you need to update your PR with upstream changes from the `master` branch, please use the `git rebase` tool, rather than `git merge`. This helps keep your commit history clean and readable, and therefore easier to understand. For example, on your local machine:

```bash
git fetch origin # updates origin/master
git checkout your-pr-branch
git rebase origin/master # rebases your changes on top of origin/master
git push your-fork your-pr-branch --force-with-lease # updates your PR, overwriting your previous changes
```

_Be able to accept constructive criticism_

Your PR may not be accepted at first. Often a reviewer will see something that you might have missed or have suggestions for a different way. Remember that suggestions are made and questions asked in order to maintain the quality and usability of the code.

TL;DR

Use the GitHub website to submit a new pull request against upstream/master.

-   Keep your PR small, with a single focus
-   Maintain a clean commit history
-   Use a style consistent with the rest of the codebase
-   Before submitting, rebase your work on the current master branch

**Resources & Additional Reading**

-   GitHub Docs: https://docs.github.com/en
-   GitHub Guides: https://guides.github.com/
-   git cheatsheet: https://github.github.com/training-kit/downloads/github-git-cheat-sheet.pdf
-   git-scm: https://git-scm.com/
-   git how-to: https://githowto.com/
-   dangit git!: https://dangitgit.com/
-   lorem ipsum generator: https://www.lipsum.com/

Hi! Added as part of today's task.
