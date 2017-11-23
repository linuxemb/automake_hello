#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.61])
AC_INIT([hello], [1.0], [hello-bugs@example.org])
AM_INIT_AUTOMAKE([silent-rules])
AC_CONFIG_SRCDIR([hello.c])

# Checks for programs.
AC_PROG_CC
AC_PROG_INSTALL


AC_CONFIG_FILES([Makefile])
AC_OUTPUT

echo \
"-------------------------------------------------

 ${PACKAGE_NAME} Version ${PACKAGE_VERSION}

 Prefix: '${prefix}'.
 Compiler: '${CC} ${CFLAGS} ${CPPFLAGS}'

 Package features:
   Async Execution: ${async_exec}

 Now type 'make @<:@<target>@:>@'
   where the optional <target> is:
     all                - build all binaries
     install            - install everything

--------------------------------------------------"
