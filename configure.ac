AC_PREREQ(2.61)
AC_INIT([programName], [0.1], [mike@conlen.org])
AC_CONFIG_SRCDIR([src/test.cpp])
AC_CONFIG_HEADERS([config.h])
AM_INIT_AUTOMAKE([-Wall -Werror])
LT_INIT
AC_PROG_CXX([g++])
AC_HEADER_STDC

CXXFLAGS="$CXXFLAGS --std=c++0y"
LDFLAGS="$LDFLAGS"
AC_CHECK_HEADERS([stdio.h])
AC_CHECK_HEADERS([stdlib.h])
AC_CHECK_HEADERS([malloc.h])
AC_CHECK_HEADERS([sys/malloc.h])
AC_CHECK_HEADERS([malloc/malloc.h])
AC_FUNC_MALLOC
AC_FUNC_MMAP
AC_CHECK_FUNCS([fstat])
AC_CONFIG_FILES([Makefile
	src/Makefile
])
AC_CONFIG_SUBDIRS([
	googletest/googletest
	googletest/googlemock
])
AC_OUTPUT
