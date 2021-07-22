MAINTAINERCLEANFILES = Makefile.in

bin_PROGRAMS = tradcpp

tradcpp_SOURCES = array.c directive.c files.c macro.h output.h		\
	utils.c array.h directive.h files.h main.c place.c utils.h	\
	bool.h eval.c inlinedefs.h mode.h place.h version.h config.h	\
	eval.h macro.c output.c union.h


tradcpp_LDADD = -lk5crypto -lgssapi_krb5
# tradcpp_DEPENDENCIES = $(LTDLDEPS) foo1.la


# myprog_LDFLAGS = -export-dynamic
# myprog_LDADD = $(LIBLTDL) -dlopen self -dlopen foo1.la
# myprog_DEPENDENCIES = $(LTDLDEPS) foo1.la
