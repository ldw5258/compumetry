#                                               -*- Autoconf -*- 
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.65])
AC_INIT([compumetry],[1.0.0], [ldw5258@126.com])
AC_CONFIG_SRCDIR([config.h.in])
AC_CONFIG_HEADERS([config.h])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])

# Checks for programs.
AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_LIBTOOL
AC_CONFIG_MACRO_DIR([m4])
# Checks for libraries.
dnl # Force to dynamic
dnl AC_DISABLE_STATIC

# Checks for header files.
AC_CHECK_HEADERS([stdlib.h string.h unistd.h stdio.h limits.h])
# Checks for typedefs, structures, and compiler characteristics.

# Checks for library functions.

AC_CONFIG_FILES([
Makefile
src/Makefile
lib/Makefile
])
AC_OUTPUT
