ACLOCAL_AMFLAGS=-I m4
lib_LTLIBRARIES = libposition_component.la
libposition_component_la_SOURCES = position_component.cpp
libposition_component_la_CXXFLAGS = -std=c++17 ${LIBECS_CFLAGS} ${JSONCPP_CFLAGS}
libposition_component_la_LDFLAGS = -no-undefined
libposition_component_la_LIBADD = ${LIBECS_LIBS} ${JSONCPP_LIBS}
