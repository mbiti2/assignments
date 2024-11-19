 ## Section 1:System Architecture 
1.  B
2.  BIOS is a firmware that boots system from the first sector of the hard disk called MBR while UEFI uses a spefic partition to boot the system.
   -The BIOS supports a maximum of 2TB disk space while UEFI supports a maximum of 16TB.
3. ```lsmod``` run the command ```modprobe dummy``` to load the new module
4. /proc directory in linux is the directory that stores information about the cpu memory and the /sys directory stores systerm information
 ## Section 2:Linux installation and Package Management 
5. C
6. apt command is user friendly while dpkg is more close to the system
7. apt --purge
8. 
  ## Section 3: GNU and Unix Commands
9. B
10. grep "error" /var/log/syslog | wc -l
11. hard links are links that points to the inode of a file while soft links are links that points to the path of a file. Hard links have thesame meta data as the original file while soft links do not
 the command to create a hard link is ```ln filename newname``` while command to create a soft link is ```ln -s filename newname```
12. ```find /ete -type f -name "*.conf$" -mtime 7```
13. cron daemon is an application that runs automated tasks in the background. it is used to schedule or automate tasks or jobs
    00 24 * * * ./backup.sh
    ## Section 4: Devices, filesystems, and FHS
14. B
15. ```blkid```
16. ext3 supports journaling  while ext4 is more performance than ext3
    ext4 is more reliable than ext3 becuase it is more performant
    ext4 is a newer vission of ext3
17. . run the commmand ```fdisk "diskname"``` to be able to write on the partition table
    . run the commend ```mkfs.ext4 "diskname"``` to create an ext4 filesystem on the disk
    . run the command ```mount -t "fs type" "diskname" /data```
18. /etc/fstab is a file that stores configuration for the file system table. it shows the filesystem, mountpoint, types etc.

    
        
    ## Bonus Question
    - post
    - Bootloader is being loaded
    - Bootloader loads the kernel and starts it initialisation
    - init program start the service. 
    
