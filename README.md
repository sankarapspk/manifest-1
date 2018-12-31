# manifest

# Future-OS #

### Sync ###

```bash

# Initialize local repository
repo init -u https://github.com/future-os/manifest -b pie
```
```bash
# Sync
repo sync -c -jx --force-sync --no-clone-bundle --no-tags
```

### Build ###

```bash
# Set up environment
$ . build/envsetup.sh
```

```bash
# Choose a target
$ lunch aosp_$device-userdebug
```

```bash
# Build the code
$ mka bacon -jX
```
