# PersistentRamDisk
A script managing various persistent RAM disks.

RAM disks are created for firefox profile and /var/log. 
At startup, data is copied from hard drive to RAM. At 
shutdown data is copied from RAM back to hard drive.
Data can also be synched by any job scheduler. 

