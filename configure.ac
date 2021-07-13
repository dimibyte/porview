AC_INIT([porview], [0.1])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])
AC_PROG_CXX
AC_SUBST([FLTK_CXXFLAGS], [`fltk-config --cxxflags`])
AC_SUBST([FLTK_LDFLAGS], [`fltk-config --ldflags`])
AC_CONFIG_FILES([Makefile])
AC_OUTPUT

dnl# add warnings and optimization to compiler switches:
if test -n "$GXX"; then
    # GNU C compiler
    CFLAGS="-Wall -O2"
    CFLAGS_D="-Wall -g -DDEBUG"
    CXXFLAGS="-Wall -O2"
    CXXFLAGS_D="-Wall -g -DDEBUG"
else
    # generic C compiler:
    CFLAGS="-O"
    CFLAGS_D="-g -DDEBUG"
    CXXFLAGS="-O"
    CXXFLAGS_D="-g -DDEBUG"
fi
