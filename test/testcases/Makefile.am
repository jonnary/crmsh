#
# Author: Sun Jiang Dong <sunjd@cn.ibm.com>
# Copyright (c) 2004 International Business Machines
#
# This program is free software; you can redistribute it and/or
# modify it under the terms of the GNU General Public License
# as published by the Free Software Foundation; either version 2
# of the License, or (at your option) any later version.
# 
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
# 
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 59 Temple Place - Suite 330, Boston, MA  02111-1307, USA.
#
MAINTAINERCLEANFILES = Makefile.in

testcasesdir		= 	$(datadir)/$(PACKAGE)/tests/testcases
testcases_SCRIPTS	=	ra.filter common.filter xmlonly.sh history.pre history.post
testcases_DATA		=	basicset common.excl \
	confbasic confbasic-xml delete file \
	node ra resource shadow acl options \
	edit edit.excl rset rset-xml history \
	confbasic-xml.exp confbasic.exp delete.exp file.exp \
	node.exp ra.exp resource.exp shadow.exp acl.exp options.exp \
	edit.exp rset.exp rset-xml.exp history.exp history.excl \
	newfeatures newfeatures.exp acl.excl commit commit.exp

confbasic-xml.filter:
	ln xmlonly.sh $@

#			shouldn't need this next line...
EXTRA_DIST =		$(testcases_SCRIPTS) $(testcases_DATA)
