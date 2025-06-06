#
# CDDL HEADER START
#
# The contents of this file are subject to the terms of the
# Common Development and Distribution License (the "License").
# You may not use this file except in compliance with the License.
#
# You can obtain a copy of the license at usr/src/OPENSOLARIS.LICENSE
# or http://www.opensolaris.org/os/licensing.
# See the License for the specific language governing permissions
# and limitations under the License.
#
# When distributing Covered Code, include this CDDL HEADER in each
# file and include the License file at usr/src/OPENSOLARIS.LICENSE.
# If applicable, add the following below this CDDL HEADER, with the
# fields enclosed by brackets "[]" replaced with your own identifying
# information: Portions Copyright [yyyy] [name of copyright owner]
#
# CDDL HEADER END
#
#
# Copyright (c) 2005, 2010, Oracle and/or its affiliates. All rights reserved.
# Copyright 2015, Joyent, Inc.
#
#

include $(SRC)/lib/Makefile.lib

HDRS =		libdladm.h libdladm_impl.h libdllink.h libdlaggr.h	\
		libdlwlan.h libdlwlan_impl.h libdlvnic.h libdlvlan.h	\
		libdlmgmt.h libdlflow.h libdlflow_impl.h libdlstat.h	\
		libdlether.h libdlsim.h libdlbridge.h libdliptun.h	\
		libdlib.h libdloverlay.h

HDRDIR =	common

SUBDIRS =	$(MACH)
$(BUILD64)SUBDIRS += $(MACH64)

POFILE =	libdladm.po
MSGFILES =	common/libdladm.c common/linkprop.c common/secobj.c	\
		common/libdllink.c common/libdlaggr.c	\
		common/libdlwlan.c common/libdlvnic.c	\
		common/libdlvlan.c common/libdlmgmt.c	\
		common/flowattr.c common/flowprop.c	\
		common/propfuncs.c common/libdlflow.c	\
		common/libdlstat.c common/flowattr.c	\
		common/libdlether.c common/libdlsim.c	\
		common/libdlbridge.c common/libdliptun.c\
		common/libdlib.c

XGETFLAGS =     -a -x libdladm.xcl

TYPECHECK_LIB = libdladm.so.1
TYPELIST = \
	   overlay_ioc_create_t \
	   overlay_ioc_activate_t \
	   overlay_ioc_delete_t \
	   overlay_ioc_nprops_t \
	   overlay_ioc_propinfo_t \
	   overlay_ioc_prop_t \
	   dlmgmt_door_setattr_t \
	   dlmgmt_door_createid_t \
	   dlmgmt_door_destroyid_t \
	   dlmgmt_door_remapid_t \
	   dlmgmt_door_upid_t \
	   dlmgmt_door_createconf_t \
	   dlmgmt_door_setattr_t \
	   dlmgmt_door_unsetattr_t \
	   dlmgmt_door_writeconf_t \
	   dlmgmt_door_removeconf_t \
	   dlmgmt_door_destroyconf_t \
	   dlmgmt_door_openconf_t \
	   dlmgmt_door_getconfsnapshot_t \
	   dlmgmt_door_getattr_t \
	   dlmgmt_createconf_retval_t \
	   dlmgmt_openconf_retval_t \
	   dlmgmt_getconfsnapshot_retval_t \
	   dlmgmt_door_zoneboot_t \
	   dlmgmt_remapid_retval_t \
	   dlmgmt_createid_retval_t \
	   overlay_ioc_create_t \
	   overlay_ioc_activate_t \
	   overlay_ioc_delete_t \
	   overlay_ioc_nprops_t \
	   overlay_ioc_propinfo_t \
	   overlay_ioc_prop_t

all :=		TARGET = all
clean :=	TARGET = clean
clobber :=	TARGET = clobber
install :=	TARGET = install

.KEEP_STATE:

all clean clobber install: $(SUBDIRS)

install_h:	$(ROOTHDRS)

check:		$(CHECKHDRS) $(TYPECHECK)

$(POFILE):	pofile_MSGFILES

_msg:		$(MSGDOMAINPOFILE)

$(SUBDIRS): FRC
	@cd $@; pwd; $(MAKE) $(TARGET)

FRC:

include $(SRC)/Makefile.msg.targ
include $(SRC)/lib/Makefile.targ
