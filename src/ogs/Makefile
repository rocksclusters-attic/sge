#
# $Id: Makefile,v 1.8 2012/11/27 00:49:31 phil Exp $
#
# @Copyright@
# 
# 				Rocks(r)
# 		         www.rocksclusters.org
# 		         version 5.6 (Emerald Boa)
# 		         version 6.1 (Emerald Boa)
# 
# Copyright (c) 2000 - 2013 The Regents of the University of California.
# All rights reserved.	
# 
# Redistribution and use in source and binary forms, with or without
# modification, are permitted provided that the following conditions are
# met:
# 
# 1. Redistributions of source code must retain the above copyright
# notice, this list of conditions and the following disclaimer.
# 
# 2. Redistributions in binary form must reproduce the above copyright
# notice unmodified and in its entirety, this list of conditions and the
# following disclaimer in the documentation and/or other materials provided 
# with the distribution.
# 
# 3. All advertising and press materials, printed or electronic, mentioning
# features or use of this software must display the following acknowledgement: 
# 
# 	"This product includes software developed by the Rocks(r)
# 	Cluster Group at the San Diego Supercomputer Center at the
# 	University of California, San Diego and its contributors."
# 
# 4. Except as permitted for the purposes of acknowledgment in paragraph 3,
# neither the name or logo of this software nor the names of its
# authors may be used to endorse or promote products derived from this
# software without specific prior written permission.  The name of the
# software includes the following terms, and any derivatives thereof:
# "Rocks", "Rocks Clusters", and "Avalanche Installer".  For licensing of 
# the associated name, interested parties should contact Technology 
# Transfer & Intellectual Property Services, University of California, 
# San Diego, 9500 Gilman Drive, Mail Code 0910, La Jolla, CA 92093-0910, 
# Ph: (858) 534-5815, FAX: (858) 534-7345, E-MAIL:invent@ucsd.edu
# 
# THIS SOFTWARE IS PROVIDED BY THE REGENTS AND CONTRIBUTORS ``AS IS''
# AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO,
# THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
# PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE REGENTS OR CONTRIBUTORS
# BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
# CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
# SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR
# BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
# WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE
# OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN
# IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
# 
# @Copyright@
#
# $Log: Makefile,v $
# Revision 1.8  2012/11/27 00:49:31  phil
# Copyright Storm for Emerald Boa
#
# Revision 1.7  2012/09/07 22:40:40  clem
# Upgraded Grid Engine from version SGE6.2u5p2 (with patches to p3) to GE2011.11p1
#
# Revision 1.6  2012/06/11 23:43:05  clem
# Argh! JNDI interface didn't make it in Rocks 6.0 cos I commited the fix in
# sge and not in ogs! :-(
#
# Revision 1.5  2012/05/06 05:49:42  phil
# Copyright Storm for Mamba
#
# Revision 1.4  2012/05/05 01:02:53  clem
# SGE6.2u5p3 security patch (tested)
#
# Revision 1.3  2012/03/08 02:58:53  clem
# now it should work in 5.7 too
#
# Revision 1.2  2011/07/23 02:31:35  phil
# Viper Copyright
#
# Revision 1.1  2011/06/10 23:45:56  anoop
# Added Open Grid Scheduler to the SGE roll.
#
# Revision 1.43  2010/09/07 23:53:25  bruno
# star power for gb
#
# Revision 1.42  2009/12/02 23:34:58  bruno
# one more time
#
# Revision 1.41  2009/12/01 20:28:44  bruno
# still need to patch
#
# Revision 1.40  2009/11/27 18:25:00  bruno
# new version
#
# Revision 1.39  2009/05/01 19:07:22  mjk
# chimi con queso
#
# Revision 1.38  2009/04/25 03:56:02  bruno
# tweaks
#
# Revision 1.37  2009/04/21 23:43:55  bruno
# refresh bits
#
# Revision 1.36  2008/11/30 19:32:48  anoop
# Added support for SGE on Solaris
#
# Revision 1.35  2008/10/18 00:56:14  mjk
# copyright 5.1
#
# Revision 1.34  2008/09/04 21:25:37  bruno
# build fix -- thanks 'noop dog!
#
# Revision 1.33  2008/04/22 23:07:22  bruno
# qlogin and qrsh now works with latest SGE
#
# Revision 1.32  2008/03/06 23:41:58  mjk
# copyright storm on
#
# Revision 1.31  2008/02/29 18:38:45  bruno
# refresh SGE
#
# Revision 1.30  2007/06/23 04:04:01  mjk
# mars hill copyright
#
# Revision 1.29  2007/05/25 20:55:47  bruno
# first pass at version 6.1
#
# Revision 1.28  2007/04/10 10:24:41  ssy
# Change openssl installation path
#
# Revision 1.27  2007/04/03 14:34:40  ssy
# Add SGE WSGram support
# Old Pre-wsgram removed
# Not fully tested yet!
#
# Revision 1.26  2007/01/09 01:27:16  mjk
# missing file for sge gram
#
# Revision 1.25  2006/09/11 22:50:17  mjk
# monkey face copyright
#
# Revision 1.24  2006/08/10 00:12:00  mjk
# 4.2 copyright
#
# Revision 1.23  2006/08/09 18:44:23  mjk
# fix target for sge.pm
#
# Revision 1.22  2006/08/08 01:39:22  mjk
# i think this is everything the GRAM needs now
#
# Revision 1.21  2006/08/08 00:59:18  mjk
# tweak file location (more to come)
#
# Revision 1.20  2006/08/02 22:23:37  mjk
# added GRAM to SGE rpm
#
# Revision 1.19  2006/06/26 20:11:03  bruno
# added patch to do better cleanup on MPI programs that are launched from
# SGE. that is, qdel will correctly cleanup all the processes
#
# Revision 1.18  2006/06/26 19:05:37  bruno
# refreshed to version 6 update 8
#
# Revision 1.17  2005/12/30 18:28:08  mjk
# remove all spec files
#
# Revision 1.16  2005/10/12 18:10:56  mjk
# final copyright for 4.1
#
# Revision 1.15  2005/09/16 01:04:34  mjk
# updated copyright
#
# Revision 1.14  2005/09/15 18:15:25  bruno
# i386 sge v6 updates
#
# Revision 1.13  2005/08/25 17:53:34  bruno
# cleanup
#
#

PKGROOT		= /opt/gridengine
REDHAT.ROOT     = $(CURDIR)/../../

-include $(ROCKSROOT)/etc/Rules.mk
include Rules.mk

build:
	$(TAR) -xzf $(NAME)$(VERSION).tar.gz
	cd $(NAME)$(VERSION); patch -p1 < ../patch
	cd $(NAME)$(VERSION)/source; ./aimk -only-depend -no-dump;
	cd $(NAME)$(VERSION)/source; ./scripts/zerodepend;
	cd $(NAME)$(VERSION)/source; ./aimk -no-dump -sys-libssl depend;
	cd $(NAME)$(VERSION)/source; ./aimk -no-dump -sys-libssl -no-java -no-gui-inst;
	cd $(NAME)$(VERSION)/source; ./aimk -no-dump -man;

install::
	mkdir -p $(ROOT)/$(PKGROOT)
	( 						\
		cd $(NAME)$(VERSION)/source;		\
		SGE_ROOT=$(ROOT)/$(PKGROOT)	\
		./scripts/distinst -local -y -noexit	\
			-allall $(SGE_ARCH);		\
	)

clean::
	rm -rf $(NAME)$(VERSION)
