MAINTAINERCLEANFILES = Makefile.in

bin_PROGRAMS = dtfile_copy

dtfile_copy_CFLAGS = -DSHAPE

if SOLARIS
dtfile_copy_CFLAGS += -xF
endif

dtfile_copy_LDADD = @DTCLIENTLIBS@ -lXm $(TIRPCLIB) $(XTOOLLIB)

dtfile_copy_SOURCES = main_dtcopy.c   copydialog.c    overwrtdialog.c dosync.c \
		      fsrtns.c  utils.c  errordialog.c   sharedFuncs.c
