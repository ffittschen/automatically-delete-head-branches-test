# Automatically Delete Head Branches Test
Test repository for [GitHub's new feature](https://github.blog/changelog/2019-07-31-automatically-delete-head-branches-of-pull-requests/) to automatically delete head branches after merged PRs.

### Result
* 👥 Head branches are deleted under the name of [the person merging the PR](https://github.com/ffittschen/automatically-delete-head-branches-test/pull/1#event-2524302354)
* ⚡️ It works very fast, usually 1 second after merging the branch
* 🔒 Protected branches [won't be deleted](https://github.com/ffittschen/automatically-delete-head-branches-test/pull/3)
