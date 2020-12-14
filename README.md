# fsearch
CLI tool to search for files by specific search terms and filters.

Requires installation of `Cravid/dehumanise`.

Example:

```
% fsearch
./LICENSE
./fsearch
./README.md
./.git/config
./.git/objects/5a/03859cca1143e2b98b61f6be91a0e951dd6479
./.git/objects/b3/d9c040cfc9ef138e821da25965b2ab8efd700a
./.git/objects/pack/pack-5217eeeb574e1e086e38f8c87e1c281e3f2bb1d5.pack
./.git/objects/pack/pack-5217eeeb574e1e086e38f8c87e1c281e3f2bb1d5.idx
./.git/objects/6c/e44457077746d609642c6ea6610a41262cf9b6
./.git/objects/64/30f34e9cfd28ec953ca0c9c2c21f6348dd3a90
./.git/objects/b6/c3f71ed6946203a8fab82e3a7e4c8169f524b0
./.git/objects/a1/e7b952634ea1132e2b54c8e12b14e820b0f8dd
./.git/objects/f1/9327616eb90f8634760c42fb0fdea7d2ccbc49
./.git/objects/1b/7493d4a7fed431cf859004a42e24b154d3543d
./.git/HEAD
./.git/info/exclude
./.git/logs/HEAD
./.git/logs/refs/heads/main
./.git/logs/refs/remotes/origin/HEAD
./.git/logs/refs/remotes/origin/main
./.git/description
./.git/hooks/commit-msg.sample
./.git/hooks/pre-rebase.sample
./.git/hooks/pre-commit.sample
./.git/hooks/applypatch-msg.sample
./.git/hooks/fsmonitor-watchman.sample
./.git/hooks/pre-receive.sample
./.git/hooks/prepare-commit-msg.sample
./.git/hooks/post-update.sample
./.git/hooks/pre-merge-commit.sample
./.git/hooks/pre-applypatch.sample
./.git/hooks/pre-push.sample
./.git/hooks/update.sample
./.git/refs/heads/main
./.git/refs/tags/v1.0.1
./.git/refs/tags/v1.0.0
./.git/refs/remotes/origin/HEAD
./.git/refs/remotes/origin/main
./.git/index
./.git/packed-refs
./.git/COMMIT_EDITMSG
```
```
% fsearch --gt 1k .
./LICENSE
./fsearch
./.git/objects/pack/pack-5217eeeb574e1e086e38f8c87e1c281e3f2bb1d5.pack
./.git/objects/pack/pack-5217eeeb574e1e086e38f8c87e1c281e3f2bb1d5.idx
./.git/hooks/pre-rebase.sample
./.git/hooks/pre-commit.sample
./.git/hooks/fsmonitor-watchman.sample
./.git/hooks/prepare-commit-msg.sample
./.git/hooks/pre-push.sample
./.git/hooks/update.sample
```
```
% fsearch . rEadMe
./README.md
```
