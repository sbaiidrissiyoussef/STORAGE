# STORAGE
Contains some automated scripts related to storage, on Linux and AIX.

####  Redhat  : Extend root directory ( / ) by script 
A script ( *extend_slash.sh* )  to extend the redhat root ( / ). Use it as follow
```bash
## 1. Add a new disk to your server ( Ex : /dev/sdb ) 
## 2. Create a new partition on the disk ( Ex : fdisk /dev/sdb )
## 3. Execute the script 
./extend_slash.sh
```
#### Redhat   : Display, Create, Remove, Extend, Reduce operations
A script ( *rhel8_storage.sh* ) that contains all managamenet commands ( dynamically ) to display, create, remove, extend and reduce all the following elements : 
* Partitions
* Physical Volumes
* Volume Groups
* Logical Volumes
* Filesystems

The following schema describes the storage layer of Redhat
![Redhat Storage](https://wiki.zikossworld.com/lib/exe/fetch.php?media=informatique:linux:lvm.jpg)


*Creator : Youssef Sbai Idrissi, 2020*
