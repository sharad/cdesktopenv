MAINTAINERCLEANFILES = Makefile.in

noinst_LTLIBRARIES = libmgrs.la

libmgrs_la_CXXFLAGS = -DC_API -DCOMPACTED_DISK_REP -DPORTABLE_DB -I.. \
		      -I../dti_excs

libmgrs_la_SOURCES = managers.C misc.C query_mgr.C template_mgr.C
