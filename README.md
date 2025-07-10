# This is Local Manifest

### Init YAAP Manifest

```
repo init -u https://github.com/yaap/manifest.git -b sixteen --git-lfs
```

### Clone Repository

```
git clone https://github.com/mvimal2607/local_manifest.git .repo/local_manifests
```

### Start Sync 

```
repo sync -j$(nproc --all) --no-tags --no-clone-bundle --current-branch
```
