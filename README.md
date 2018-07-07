# lfs-demo

*this repo contains some big files tracked via [LFS](https://git-lfs.github.com/) in the lfs branch*

-> Setup LFS

```bash
git lfs install
git lfs track "img/**"
git add img/test.jpg
git lfs ls-files
```

-> Switching branches downloads referenced LFS files

```bash
$ git checkout lfs
Filtering content: 100% (5/5), 21.01 MiB | 608.00 KiB/s, done.
Branch 'lfs' set up to track remote branch 'lfs' from 'origin'.
Switched to a new branch 'lfs'
```
