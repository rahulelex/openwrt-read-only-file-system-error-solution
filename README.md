# Openwrt Read Only File-System Error Solution
This repository provides a solution to the issue of a read-only file system in **OpenWrt**. When attempting to create or modify any file, OpenWrt displays a read-only file system error.
## Use below command to resolve the error.
```sh
e2fsck /dev/mmcblk0p2
```
- After executing the above command, you simply need to type **y** when prompted.
- The **e2fsck** will fix the corrupted file system.
## License
**Free Software, Hell Yeah!**

## Authors
- [Rahul Gupta](https://github.com/rahulelex)
