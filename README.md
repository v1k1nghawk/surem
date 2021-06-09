# Surem

* _NAME:_ surem - Secure file removal</ins>

* _SYNOPSIS:_ **surem** [FILE]...</ins>

* _DESCRIPTION:_ Linux-specific tool. Securely delete all specified FILE(s) from a mounted filesystem. WARNING: Best results are obtained on a local filesystems</ins>

* _REQUIREMENTS:_


1. Non-local filesystem(s) with FILE(s) has an **sync** option in the server's /etc/exports configuration file</ins>


2. Filesystem(s) with FILE(s) has an **sync** option in the local /etc/fstab configuration file</ins>


3. The ext3/ext4 filesystem with FILE(s) DOESN'T have an option **data=journal** in the local /etc/fstab configuration file</ins>


4. FILE(s) closed and **sync**/**fsync** performed</ins>

