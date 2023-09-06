# common-stale-action

Common stale action for all osbuild repositories. This actions makes it easy to adjust stale settings for all osbuild repositories in one place.

For now, only pull requests are checked. The action will:

* Mark pull requests as stale if they have not been updated for 30 days by adding the `Stale` label.
* Remove the `Stale` label if a pull request is updated.
* Close pull requests that have been stale for 7 days.
