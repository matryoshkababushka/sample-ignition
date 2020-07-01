# BOSS-RAID

Ignition config sample

### Notes

- /dev/sda - secondary disk to be used as ext4 RAID1 component
- /dev/sdb - secondary disk to be used as ext4 RAID1 component


`/var/lib/docker/volumes` - mount point for RAID contents.

- format.json: creates and forces wipe-and-format whole disks
- no-format.json: assumes existing (formatted) RAID disks and only mounts RAID