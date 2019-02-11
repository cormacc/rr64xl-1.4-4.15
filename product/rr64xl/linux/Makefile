#
# Copyright (C) 2013 HighPoint Technologies, Inc.
# All Rights Reserved.
#

HPT_ROOT := ../../..

C_DEFINES := -DSUPPORT_ARRAY

TARGETNAME := rr640l
TARGETTYPE := KMOD
TARGETMODS := him_rr640l.o ldm_raid50.o partition.o raid0.o raid1.o raid5.o jbod.o
TARGETOBJS := os_linux.o osm_linux.o div64.o hptinfo.o config.o

include $(HPT_ROOT)/inc/linux_32mpa/Makefile.def

$(TARGETOBJS): osm_linux.h
