bin_PROGRAMS = \
  xrdp-waitforx

AM_LDFLAGS = -lX11 -lXrandr
AM_CFLAGS = -I$(top_srcdir)/common

xrdp_waitforx_SOURCES = waitforx.c

xrdp_waitforx_LDADD = \
  $(top_builddir)/common/libcommon.la
