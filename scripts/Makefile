#
# ax-make: Alex' Simple Makefile System
# Copyright (c)2014 Alexander Barton (alex@barton.de)
#
# This library is free software; you can redistribute it and/or modify
# it under the terms of the GNU Lesser General Public License as published
# by the Free Software Foundation; either version 2.1 of the License, or
# (at your option) any later version.
#

ALL = axify

include ../Makefile.ax

install-local:
	install -d -o $(USER) -g $(GROUP) -m 755 \
	 $(DESTDIR)$(PREFIX)/bin
	install -p -o $(USER) -g $(GROUP) -m 755 axify \
	 $(DESTDIR)$(PREFIX)/bin/axify
