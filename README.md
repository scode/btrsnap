Script to backup a btrfs subvolume with tarsnap. Nothing fancy; logs
to syslog, supports sending an E-Mail on failure, does btrfs
snapshotting and the necessary snaptime management.

Usage:

  ./btrsnap /path/to/subvolume

It makes some assumptions on locations of keyfile and cache file by
default; for a list of environment variables to set to adjust, see:

  ./btrsnap --help
