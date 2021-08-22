# mergeconflict_repo

A repository that has merge conflict if attempt to merge `feature` branch into
`master`.

The state on both branches are as follows

![commit-tree](http://data.wasin.io/blog2/29/commit-tree.svg)


in short after branched out from `master` into `feature`. The latter branch
continues working on for 2 commits, but at the same time `master` branch
also had one more commit work. Attempt to merge `feature` into `master` will
result in merge conflict.

# Note

This repository is originally aimed to be used accompanying my technical blog post
no. 29 at [haxpor/blog2](https://github.com/haxpor/blog2).


# License

MIT, Wasin Thonkaew
