![Outlier.org](https://i.imgur.com/vJowpL1.png)

---

# Outlier Engineering Git Challenge

At Outlier, you will be expected to be able to contribute features and fixes without causing conflicts and other version control headaches. An important tool for keeping codebases clean is `git rebase`. This challenge will test your understanding of a basic codebase and your ability to use `git rebase` properly.

## The Challenge

There are two pull requests open on this repo. Each change is in its own branch. The challenge is to use `git rebase` to add both changes to `master`. When you are finished, your `master` branch should have three commits in the following order:

```
* feat: add base64 endpoint
* feat: add user-agent endpoint
* init
```

_ Any errors, missing features, missing tests, or failing tests will disqualify the solution. _

## Instructions

How to attempt this challenge:

1) Create a new repo in your account and note the git url
2) Clone this repo
3) Solve the challenge
4) Set your new repo as the origin: `git remote set-url origin ${your repo url}`
5) Push your solution to your repo

You must follow these steps for your solution to be accepted -- forks or other methods will not be considered.


## My Solution

```cmd
git fetch origin
git checkout master
git rebase origin/feature/base64
git rebase origin/feature/useragent
git --continure
git push origin master
```

