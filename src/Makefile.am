# Copyright (C) 2013 Eric P. Hutchins

# This file is part of libcasheph.

# libcasheph is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation, either version 3 of the License, or
# (at your option) any later version.

# libcasheph is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.

# You should have received a copy of the GNU General Public License
# along with libcasheph.  If not, see <http://www.gnu.org/licenses/>.

bin_PROGRAMS = test
test_SOURCES = test.c

test_LDADD = libcasheph.la

lib_LTLIBRARIES = libcasheph.la
libcasheph_la_SOURCES = casheph.c

include_HEADERS = casheph.h

libcasheph_la_LDFLAGS = -version-info 3:0:1
