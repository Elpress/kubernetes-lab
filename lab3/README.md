[prod-omg-1] root@m1-osd0002:ceph# /usr/sbin/udevadm info --query=property /dev/sdq
DEVLINKS=/dev/disk/by-id/scsi-36f4ee08033e19b002be7e154da4b9995 /dev/disk/by-id/wwn-0x6f4ee08033e19b002be7e154da4b9995 /dev/disk/by-path/pci-0000:af:00.0-scsi-0:3:111:0 /dev/disk/by-id/scsi-SDELL_PERC_H750_Adp_0095994bda54e1e72b009be13380e04e
DEVNAME=/dev/sdq
DEVPATH=/devices/pci0000:ae/0000:ae:00.0/0000:af:00.0/host0/target0:3:111/0:3:111:0/block/sdq
DEVTYPE=disk
ID_BUS=scsi
ID_MODEL=PERC_H750_Adp
ID_MODEL_ENC=PERC\x20H750\x20Adp\x20\x20\x20
ID_PART_TABLE_TYPE=dos
ID_PART_TABLE_UUID=6a576eb5
ID_PATH=pci-0000:af:00.0-scsi-0:3:111:0
ID_PATH_TAG=pci-0000_af_00_0-scsi-0_3_111_0
ID_REVISION=5.16
ID_SCSI=1
ID_SCSI_INQUIRY=1
ID_SCSI_SERIAL=0095994bda54e1e72b009be13380e04e
ID_SERIAL=36f4ee08033e19b002be7e154da4b9995
ID_SERIAL_SHORT=6f4ee08033e19b002be7e154da4b9995
ID_TYPE=disk
ID_VENDOR=DELL
ID_VENDOR_ENC=DELL\x20\x20\x20\x20
ID_WWN=0x6f4ee08033e19b00
ID_WWN_VENDOR_EXTENSION=0x2be7e154da4b9995
ID_WWN_WITH_EXTENSION=0x6f4ee08033e19b002be7e154da4b9995
MAJOR=65
MINOR=0
SCSI_IDENT_LUN_NAA_REGEXT=6f4ee08033e19b002be7e154da4b9995
SCSI_IDENT_SERIAL=0095994bda54e1e72b009be13380e04e
SCSI_MODEL=PERC_H750_Adp
SCSI_MODEL_ENC=PERC\x20H750\x20Adp\x20\x20\x20
SCSI_REVISION=5.16
SCSI_TPGS=0
SCSI_TYPE=disk
SCSI_VENDOR=DELL
SCSI_VENDOR_ENC=DELL\x20\x20\x20\x20
SUBSYSTEM=block
TAGS=:systemd:
USEC_INITIALIZED=5632726
[prod-omg-1] root@m1-osd0002:ceph# s -l /dev/sd
sda   sdb   sdc   sdd   sde   sdf   sdg   sdh   sdi   sdj   sdk   sdl   sdm   sdm1  sdm2  sdm3  sdn   sdn1  sdn2  sdn3  sdo   sdo1  sdo2  sdo3  sdp   sdp1  sdp2  sdp3  sdq   sdq1  sdq2  sdq3
[prod-omg-1] root@m1-osd0002:ceph# s -l /dev/sdq
-bash: s: command not found
[prod-omg-1] root@m1-osd0002:ceph#
[prod-omg-1] root@m1-osd0002:ceph#
[prod-omg-1] root@m1-osd0002:ceph#
[prod-omg-1] root@m1-osd0002:ceph#
[prod-omg-1] root@m1-osd0002:ceph#
[prod-omg-1] root@m1-osd0002:ceph#
[prod-omg-1] root@m1-osd0002:ceph# ls -l /dev/sdq
brw-rw----. 1 root disk 65, 0 Sep 26 12:45 /dev/sdq
[prod-omg-1] root@m1-osd0002:ceph# smartcl
-bash: smartcl: command not found
[prod-omg-1] root@m1-osd0002:ceph#
[prod-omg-1] root@m1-osd0002:ceph#
[prod-omg-1] root@m1-osd0002:ceph# dmesg |grep sdq
[prod-omg-1] root@m1-osd0002:ceph#
