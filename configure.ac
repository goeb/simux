#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.63])
AC_INIT([Simple TCP Multiplexer], [1.0.0], [], [simux], [http://github.com/goeb/simux])
AC_CONFIG_HEADERS([src/config.h])
AC_CANONICAL_TARGET
AM_INIT_AUTOMAKE([-Wall -Werror subdir-objects])
AM_SILENT_RULES([yes])

# Checks for programs.
AC_PROG_CXX
AC_PROG_CC
AM_PROG_CC_C_O

# Checks for external libraries.
PKG_PROG_PKG_CONFIG()
PKG_CHECK_MODULES(OPENSSL, openssl)


AC_CONFIG_FILES([Makefile])
AC_OUTPUT

