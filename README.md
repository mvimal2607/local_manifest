# This is Local Manifest

### Clone Repository

```
git clone https://github.com/mvimal2607/local_manifest.git .repo/local_manifests
```

### Start Sync 

```
repo sync -c --force-sync --optimized-fetch --no-tags --no-clone-bundle --prune -j$(nproc --all)
```
