In the RMAN script, the path of the backup file is relative to the mount point.

Cohesity recommends that you create one channel and one VIP for each Node in the Cohesity cluster. You can use the same mount point with all the channels.

The Cohesity library does not create a directory structure so you must manually create any directory structure inside the mount point. In the following examples, you must create bkp_dir inside mount point /mnt/cohesity.
