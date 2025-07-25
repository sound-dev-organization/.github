# _sound\_dev_ labels

## Issues

* `feature` - New feature issues.
* `fix` - Bug discovery issue.

## Pull requests

* `feature` - New feature PR.
* `fix` - Bug fix PR.
* `release` - Release PR. (develop -> master)

### Merge requirements

There are 2 additional labels for reviewers:

* `shipit:1`
* `shipit:2`

Reviewer should add `shipit` to the PR when they:

* finished the review
* allow PR to be merged

_Note: PR creator **must not** add `shipit` label by himself!_

Number of required `shipit` labels depends on project developers number:

* 1 developer - 0 `shipit` labels needed.
* 2 developers - 1 `shipit` label needed.
* \>2 developers - 2 `shipit` labels needed.
