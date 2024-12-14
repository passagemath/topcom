lib_LTLIBRARIES = libCHECKREG.la

libCHECKREG_la_SOURCES = \
QSOinterface.cc \
SPXinterface.cc \
LPinterface.cc \
RegularityCheck.cc

include_HEADERS = \
QSOinterface.hh \
SPXinterface.hh \
RegularityCheck.hh \
LPinterface.hh

AM_CPPFLAGS    += -I../lib-src
AM_CPPFLAGS    += -I../wrap-gmp-gmpxx
AM_CPPFLAGS    += -I../external/include
AM_CPPFLAGS    += -I$(includedir)

AM_CPPFLAGS    += -ftemplate-depth=100
