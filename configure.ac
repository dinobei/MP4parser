#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.69])
AC_INIT([mp4-parser], [1.0.0], [BUG-REPORT-ADDRESS])
AC_CONFIG_SRCDIR([stream.h])
AM_INIT_AUTOMAKE([1.0.0 foreign no-define subdir-objects])
AC_CONFIG_HEADERS([config.h])

# Checks for programs.
AC_PROG_CC
LT_INIT
AC_ENABLE_SHARED
AC_ENABLE_STATIC
AC_PROG_LIBTOOL(libtool)
# Checks for programs.
AC_PROG_CC
AC_PROG_CXX
# Checks for libraries.

# Checks for header files.
AC_CHECK_HEADERS([malloc.h memory.h stdlib.h])

# Checks for typedefs, structures, and compiler characteristics.
AC_TYPE_INT16_T
AC_TYPE_INT32_T
AC_TYPE_INT64_T
AC_TYPE_INT8_T
AC_TYPE_SIZE_T
AC_CHECK_HEADER_STDBOOL
AC_TYPE_UINT16_T
AC_TYPE_UINT32_T
AC_TYPE_UINT64_T
AC_TYPE_UINT8_T

# Checks for library functions.
AC_FUNC_MALLOC
AC_FUNC_STRNLEN
AC_CHECK_FUNCS([sqrt strcspn strtol])

AC_OUTPUT(Makefile)
