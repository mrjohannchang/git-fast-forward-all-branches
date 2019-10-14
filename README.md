# git-fast-forward-all

This small tool fast-forwards all your local branches upto corresponding remote tracking branches.
Inspired by [Can “git pull --all” update all my local branches?](https://stackoverflow.com/questions/4318161/can-git-pull-all-update-all-my-local-branches).

## Usage

```
git fetch --all  # Optional
git fast-forward-all
```

Example output:

```
master
dev
  fast-forwarded
hotfix
  skipped (diverged)
```

## Installation

Copy `git-fast-forward-all` to your `$PATH` (such as `~/bin`).

## License

[Mozilla Public License Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/)
