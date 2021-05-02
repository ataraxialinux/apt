
bin_PROGRAMS = gensrclist countpkglist
bin_SCRIPTS = genbasedir

EXTRA_DIST = genbasedir

LDADD = ../apt-pkg/libapt-pkg.la $(RPM_LIBS)

gensrclist_SOURCES = gensrclist.cc cached_md5.cc cached_md5.h genutil.h
countpkglist_SOURCES = countpkglist.cc
