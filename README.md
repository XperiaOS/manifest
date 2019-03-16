XperiaOS
========

To initialize your local repository, use this command:

	repo init -u https://github.com/XperiaOS/manifest.git -b pie
  
 Then to sync up:

```bash
repo sync -f --force-sync --no-tags --no-clone-bundle -j$(nproc --all)
```

