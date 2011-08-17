## Makefile.am
## 14.07.2000

SUBDIRS            = icon

bin_PROGRAMS       = gtkguitune

gtkguitune_SOURCES = main.cc \
                     guitune.cc lcdview.cc logview.cc osziview.cc \
                     guitune.h  lcdview.h  logview.h  osziview.h  \
                     resources.h FB_logo.xpm \
                     aboutbox.c aboutbox.h

gtkguitune_LDADD   = @GTKMM_LIBS@
INCLUDES           = @GTKMM_CFLAGS@
