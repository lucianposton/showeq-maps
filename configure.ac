dnl Process this file with autoconf to produce a configure script.
dnl $Id: configure.ac,v 1.3 2004/09/22 05:30:22 dohpaz Exp $ $Name:  $

AC_PREREQ(2.53)
AC_INIT()
AM_INIT_AUTOMAKE(showeq-maps, 1.0)
AM_MAINTAINER_MODE
PARENTPACKAGE=showeq

AC_SUBST(PARENTPACKAGE)

AC_DEFUN(SUCCESS,[
echo "Success!"
case $target_os in
  solaris*)
    echo "<insert build instructions here>"
    ;;
  freebsd*)
    echo "Please run:"
    echo "  gmake"
    ;;
  linux*)
    echo "Please run:"
    echo "  make"
    ;;
esac
])

AC_OUTPUT([Makefile maps/Makefile])
SUCCESS
