# Bootcamp
# 20 Points
# We found an old floppy-drive laying around and think that there may be a flag hidden on it somewhere. We managed to copy the drive image,
# but there doesn't appear to be any kind of filesystem on it. In fact, all of the data appears to be on the first sector of the disk.

### Solution
    After downloading the image i ran it against qemu and the flag was present for the user to see 
    qemu-system-i386 floppy.img 
    Flag:ACI{BoOt_MaGiC}
