# zfs-stats

ZFS statistics tool for FreeBSD.

The `zfs-stats` script displays general ZFS information
and human-readable statistics for the following subsystems:

* ARC
* L2ARC
* DMU (zfetch)
* vdev cache.

Help: `zfs-stats -h`

In the ports tree: [filesystems/zfs-stats][1]

Homepage: https://www.vx.sk/zfs-stats/

This script is a fork of [arc_summary.pl][2] by Jason Hellenthal.

[1]: https://www.freshports.org/filesystems/zfs-stats/
[2]: https://github.com/DataIX/main/tree/master/head/scripts/zfs/arc_summary
