# _sound\_dev_ branching strategy

## Release / pre-release branches

* `master` - production branch (releases)
* `develop` - development branch (to be released features)

## Feature / fix branches

* `feature/<issue_id>_<description>` - feature branch
* `fix/<issue_id>_<description>` - fix branch

Each feature / fix branch should contain **only 1 commit** for easier tracking. Please, use `git commit --amend` after first commit, or stash all the commits before PR.
