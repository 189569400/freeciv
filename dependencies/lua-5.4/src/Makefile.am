## Process this file with automake to produce Makefile.in

noinst_LTLIBRARIES = liblua.la

AM_CPPFLAGS =

liblua_la_LIBADD = -lm

liblua_la_SOURCES = 	\
	localluaconf.h	\
	lapi.c		\
	lapi.h		\
	lauxlib.c	\
	lauxlib.h	\
	lbaselib.c	\
	lcode.c		\
	lcode.h		\
	lcorolib.c	\
	lctype.c	\
	lctype.h	\
	ldblib.c	\
	ldebug.c	\
	ldebug.h	\
	ldo.c		\
	ldo.h		\
	ldump.c		\
	lfunc.c		\
	lfunc.h		\
	lgc.c		\
	lgc.h		\
	linit.c		\
	liolib.c	\
	ljumptab.h	\
	llex.c		\
	llex.h		\
	llimits.h	\
	lmathlib.c	\
	lmem.c		\
	lmem.h		\
	loadlib.c	\
	lobject.c	\
	lobject.h	\
	lopcodes.c	\
	lopcodes.h	\
	lopnames.h	\
	loslib.c	\
	lparser.c	\
	lparser.h	\
	lprefix.h	\
	lstate.c	\
	lstate.h	\
	lstring.c	\
	lstring.h	\
	lstrlib.c	\
	ltable.c	\
	ltable.h	\
	ltablib.c	\
	ltm.c		\
	ltm.h		\
	luaconf.h	\
	lua.h		\
	lua.hpp		\
	lualib.h	\
	lundump.c	\
	lundump.h	\
	lutf8lib.c	\
	lvm.c		\
	lvm.h		\
	lzio.c		\
	lzio.h


if !SYS_TOLUA_CMD

EXTRA_DIST = \
	dist-stamp

# To trick 'make dist' to build tolua, needed later to generate source files
dist-stamp : liblua.la
	touch dist-stamp

DISTCLEANFILES = dist-stamp

endif
