AC_PREREQ([2.69])
AC_INIT([position_component], [1.0.2], [tim@metaverse.systems], [position_component], [https://metaverse.systems])
AC_CONFIG_HEADERS([config.h])
AC_PROG_CXX
AM_INIT_AUTOMAKE([subdir-objects])
LT_INIT([disable-static])

AC_CONFIG_MACRO_DIR([m4])

PKG_CHECK_MODULES([LIBECS], ecs-cpp)
PKG_CHECK_MODULES([JSONCPP], jsoncpp)

AC_OUTPUT(Makefile src/Makefile)
