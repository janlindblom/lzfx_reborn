AC_INIT
AC_CONFIG_SRCDIR([lzfx.c])

AC_USE_SYSTEM_EXTENSIONS
AC_SYS_LARGEFILE
AC_PROG_CC
AC_PROG_RANLIB
AC_PROG_INSTALL
m4_warn([obsolete],
[The preprocessor macro `STDC_HEADERS' is obsolete.
  Except in unusual embedded environments, you can safely include all
  ISO C90 headers unconditionally.])dnl
# Autoupdate added the next two lines to ensure that your configure
# script's behavior did not change.  They are probably safe to remove.
AC_CHECK_INCLUDES_DEFAULT
AC_PROG_EGREP


AC_C_CONST
AC_C_INLINE

if test "$GCC" = yes; then
   CFLAGS="$CFLAGS -O3 -funroll-all-loops"
else
   AC_MSG_RESULT(no gcc)
fi

AC_CONFIG_FILES([Makefile])
AC_OUTPUT
