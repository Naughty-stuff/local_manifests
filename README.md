# Clone Source

```bash
git clone -b sweet https://github.com/Naughty-stuff/local_manifests --depth=1 .repo/local_manifests
```
# Then to sync up:
```
repo sync -c -j8 --force-sync --no-clone-bundle --no-tags
```
