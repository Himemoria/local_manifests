# Local Manifests #
Just grab the manifest and sync to get device sources

### AOSP R ###

# Grab Local Manifest
```bash
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/Himemoria/local_manifests/master/eleven.xml --create-dirs
```

# Sync
```bash
repo sync -j$(nproc --all) --force-sync
```

### AOSP S R-VENDOR ###

# Grab Local Manifest
```bash
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/Himemoria/local_manifests/master/twelve.xml --create-dirs
```

# Sync
```bash
repo sync -j$(nproc --all) --force-sync
```

### AOSP S S-VENDOR ###

# Grab Local Manifest
```bash
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/Himemoria/local_manifests/master/twelve-s.xml --create-dirs
```

# Sync
```bash
repo sync -j$(nproc --all) --force-sync
```
