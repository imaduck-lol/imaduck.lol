---
layout: default
---

I came across this issue today when pushing to a new github account completely unrelated to anything you may be reading now. `git push` only wanted to use my default ssh key and thus my other github account. It [appears to have something to do with caching](https://stackoverflow.com/q/5335197) but thanks to [Hustlion](https://stackoverflow.com/users/4394850/hustlion) over at [github](https://stackoverflow.com/a/43953433), I was able to get it working with the following command:

    GIT_SSH_COMMAND='ssh -i ~/.ssh/your_private_key' git COMMAND
