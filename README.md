# Local Manifests #
Just grab the manifest and sync to get device sources

### AOSP R ###
```bash
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/Himemoria/local_manifests/master/eleven.xml --create-dirs
```

### AOSP S R-VENDOR ###
```bash
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/Himemoria/local_manifests/master/twelve.xml --create-dirs
```

### AOSP S S-VENDOR ###
```bash
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/Himemoria/local_manifests/master/twelve-s.xml --create-dirs
```

### AOSP T S-VENDOR ###
```bash
curl -o .repo/local_manifests/local_manifests.xml https://raw.githubusercontent.com/Himemoria/local_manifests/master/thirteen.xml --create-dirs
```

### SYNC ###
```bash
repo sync -j$(nproc --all) --force-sync
```
