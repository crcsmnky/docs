The default journal commit interval is 100 milliseconds if a single
block device (e.g. physical volume, RAID device, or LVM volume)
contains both the journal and the data files.

If the journal is on a different block device than the data files the
default journal commit interval is 30 milliseconds.
