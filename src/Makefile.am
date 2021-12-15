## Process this file with automake to produce Makefile.in

INCLUDES = \
	-DPACKAGE_DATA_DIR=\""$(datadir)"\" \
	-DPACKAGE_LOCALE_DIR=\""$(prefix)/$(DATADIRNAME)/locale"\" \
	@PACKAGE_CFLAGS@

bin_PROGRAMS = capteur2

capteur2_SOURCES = \
	main.c \
	support.c support.h \
	interface.c interface.h \
	callbacks.c callbacks.h \
	capteur2.c capteur2.h \
	personne.c personne.h \
	reclamation.c reclamation.h \
	menu.c menu.h \
	fonction.c fonction.h \
	verifier.c verifier.h

capteur2_LDADD = @PACKAGE_LIBS@ $(INTLLIBS)

