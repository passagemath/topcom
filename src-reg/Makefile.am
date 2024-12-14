bin_PROGRAMS = checkregularity

checkregularity_SOURCES = checkregularity.cc

LDADD           = ../lib-src/libTOPCOM.a \
                  ../lib-src-reg/libCHECKREG.a \
                  -lgmpxx -lgmp


if USE_QSOPTEX
LDADD          += ../external/lib/libqsopt_ex.a
endif

if USE_SOPLEX
LDADD          += ../external/lib/libsoplex.a
endif

AM_CPPFLAGS    += -I../lib-src
AM_CPPFLAGS    += -I../lib-src-reg
AM_CPPFLAGS    += -I../wrap-gmp-gmpxx
AM_CPPFLAGS    += -I../external/include
AM_CPPFLAGS    += -I$(includedir)

AM_CPPFLAGS    += -ftemplate-depth=100
