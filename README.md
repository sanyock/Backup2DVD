Backup2DVD
==========

Aulix Backup2DVD utility does VERY VERY SUPER RELIABLE backups to optical disks like Bluray and DVD, data on backup media survives scratches due to high redundancy



Aulix Backup2DVD utilizes following software:

     7zip (default)
    or rar (for double redundancy - generally it is a waste of space)
    genisoimage
    dvdisaster (high redundancy of 30% at the whole medium level)
    dvd+rw-format
    growisofs
    md5sum
    dd

The program uses ssh to connect to a Linux host, it works with above programs via a network layer
without direct linking which is allowed by GPL for proprietary software. It expects the open source programs at their default location as installed from their packages by default.

Aulix Backup2DVD utility combines a power of the best backup utilities available today and brings to you
a convenient CLI (command line interface) to manage the whole process.
Features

    Compresses and archives your directory by rar into multiple volumes with a file level redundancy.
    Then creates ISO files contaning rar volumes.
    Processes them by dvdisaster utility to add more high redundancy at the level of the whole medium.
    Burns ISO images to multiple mediums.
    Verifies writing results.
    Backup2DVD executable (Aulix.Utils.Backup2DVD.exe) can run in any DotNet enabled environment including Windows .NET framework v2 and Mono on Linux, it has a CLI.
    Backup2DVD has been tested under Debian Linux and Microsoft Windows.

Backup2DVD will save your optical backups for a duration of many years.
