# Autotagger

[![CircleCI](https://circleci.com/gh/thewoolleyman/infrastructure-as-code-example-aws.svg?style=svg)](https://circleci.com/gh/thewoolleyman/infrastructure-as-code-example-aws)

***NOTE: This CircleCI config is NOT related to the actual tutorial. You probably don't care 
about it and can just ignore this whole `.circleci` directory.***

If you are curious, it is only used to run
[git-revisionist-historian](https://github.com/thewoolleyman/git-revisionist-historian)
in order to automatically keep the tags up-to-date for the incremental commits. Otherwise, when 
the master branch is rebased and the SHA's change the tags would become stale.