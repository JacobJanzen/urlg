AC_PREREQ([2.65])
AC_INIT([urlg], [0.0.1-alpha], [jacob.a.s.janzen@gmail.com])
AC_CONFIG_SRCDIR([src/main.c])
AC_CONFIG_AUX_DIR([build-aux])

AC_PROG_CC
AC_CHECK_LIB([curses], [initscr])
AC_CHECK_HEADERS([curses.h])

AM_INIT_AUTOMAKE([foreign -Wall -Werror])

AC_CONFIG_HEADERS([config.h])
AC_CONFIG_FILES([Makefile src/Makefile])

AC_OUTPUT
