# Vmware-Customization 1.0

Currently the customization playbook handles:

0) Data from JSON file
1) Five network types - Production(aliases also included), Management, NFS, Backup, BE
2) A single interface on a single network, the ratio is 1:1 
3) Three DNS servers ( Configuring more than 3 is useless )
4) *New* Filesystem on top of disks mapping via scsi_id, both from command line and facts
5) For the above filesystems, the ratio is 1:1 against the disk. It manage ext4/xfs
6) Network File System






ROADMAP:
1.0 = First Release and testing\n
2.0 = Rollback incomplete tasks in case of failure
3.0 = Handles multiple systems in a single JSON file
