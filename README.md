This is a package to restore the stock kernel and modules by flashing a zip.
The kernel package must contain these commits:
 https://github.com/DD3Boh/AnyKernel2/commit/0d8964325e531041ec4e2bb7572d6730919b7608

 https://github.com/DD3Boh/AnyKernel2/commit/c7544bfc53a7fa38bed5bd97ccfb705e4dd6a584

The stock kernel boot.img and the modules folder get backuped while flashing the kernel and they gets saved into:
sdcard/restore

there is also a file to check if the backup has already been done or not and it's into:
sdcard/backup-check

Tested on a zuk z2 with android nougat 7.1.2