# GIT workflow

One-click solution for personalized results.

## Steps
* Each dev forks & clones repo.
* Any new features should be on their own branch w/ following naming convention:
lastName/feature/issue-tracker-number
Ex. arya/userAuth/#54

* After completing a feature, commit and push to corresponding branch on your forked repo, ensuring it passes a Travis CI build in the process.
* Create PR.
* Have at least 2 peers approve PR before merge can be made [by 2nd reviewer].
* Merge into Master.
* Whole team rebases.
* Repeat as necessary.