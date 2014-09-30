AC_PREREQ(2.61)

# package version number (not shared library version)
# odd micro numbers indicate in-progress development
# even micro numbers indicate released versions
m4_define(xvirt802154_version_major, 0)
m4_define(xvirt802154_version_minor, 1)
m4_define(xvirt802154_version_micro, 0)

m4_define([xvirt802154_version],
          [xvirt802154_version_major.xvirt802154_version_minor.xvirt802154_version_micro])
m4_define([xvirt802154_api_version],
          [xvirt802154_version_major.xvirt802154_version_minor])

AC_INIT(xvirt802154, xvirt802154_version)
AM_INIT_AUTOMAKE(xvirt802154, xvirt802154_version)
AC_CONFIG_HEADERS(config.h)

# Checks for programs.
AC_PROG_LIBTOOL
AM_PROG_CC_C_O
AC_PROG_INSTALL

AC_SUBST(xvirt802154_CFLAGS)
AC_SUBST(xvirt802154_LIBS)

AC_OUTPUT([
Makefile
src/Makefile
])

echo ""
echo "   xvirt802154 $VERSION"
echo "   ====================="
echo ""
echo "   To build the project, run \"make\""
echo ""
