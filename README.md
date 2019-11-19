# Vmware-Customization 1.0

Currently the customization playbook handles:

1) Five network types - Production(aliases also included), Management, NFS, Backup, BE
2) A single interface on a single network, the ratio is 1:1 
3) Three DNS servers ( Configuring more than 3 is useless )
4) *New* Filesystem on top of disks mapping via scsi_id, both from command line and facts
5) *New* Filesystem via NFS
