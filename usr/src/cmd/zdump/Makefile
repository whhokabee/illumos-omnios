#
# CDDL HEADER START
#
# The contents of this file are subject to the terms of the
# Common Development and Distribution License, Version 1.0 only
# (the "License").  You may not use this file except in compliance
# with the License.
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
# Copyright 2004 Sun Microsystems, Inc.  All rights reserved.
# Use is subject to license terms.
#

PROG= zdump

OBJS= zdump.o
SRCS= $(OBJS:%.o=%.c)

include ../Makefile.cmd
include ../Makefile.cmd.64

.KEEP_STATE:

CSTD= $(CSTD_GNU17)
CFLAGS += $(CCVERBOSE)
CPPFLAGS += -I$(SRC)/cmd/zic
SMATCH = off

all: $(PROG)

$(PROG): $(OBJS)
	$(LINK.c) $(OBJS) -o $@ $(LDLIBS)
	$(POST_PROCESS)

install: all $(ROOTUSRSBINPROG)

clean:
	$(RM) $(OBJS)

lint: lint_SRCS

include ../Makefile.targ
