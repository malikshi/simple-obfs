if USE_SYSTEM_SHARED_LIB
SUBDIRS = libcork src
else
SUBDIRS = libsodium libcork libudns libev src
endif

if ENABLE_DOCUMENTATION
SUBDIRS += doc
endif

ACLOCAL_AMFLAGS = -I m4
