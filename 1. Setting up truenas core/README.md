
# Setting up TrueNas Core
This is he first part of the process where I setup TrueNas Core on Virtualbox, setup pools, setup windows shares, and add a user and define its permissions.

Video: https://youtu.be/QKCJ03jkBkA

![image](https://github.com/CoolCake322/Creating-a-homelab-server-in-VirtualBox/assets/124210891/e6b8c463-7ec6-465f-aa4d-b599921f00e8)


## Notes

Personal notes

What's a pool? 
Storage pools are attached drives organized into virtual devices (vdevs). ZFS and TrueNAS periodically
reviews and “heals” whenever a bad block is discovered in a pool. Drives are arranged inside vdevs to
provide varying amounts of redundancy and performance. This allows for high performance pools, pools
that maximize data lifetime, and all situations in between

A TrueNAS dataset is a file system you create within a data storage pool. Datasets can contain files, directories (child
datasets), and have individual permissions or flags. You can encrypt datasets using either the pool encryption created
with the pool or with a separate dataset-level encryption configuration.

    


## Software Used
    

TrueNas Core: https://www.truenas.com/truenas-core/

VirtualBox: https://www.virtualbox.org/


## Reference

Video credits: UsersGeek - https://www.youtube.com/watch?v=y-pg_wO8zOs&t=424s

Truenas Core documentation: https://www.truenas.com/docs/files/CORE12.0Docs.pdf
