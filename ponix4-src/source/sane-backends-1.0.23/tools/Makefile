# Makefile.in generated by automake 1.11.1 from Makefile.am.
# tools/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994, 1995, 1996, 1997, 1998, 1999, 2000, 2001, 2002,
# 2003, 2004, 2005, 2006, 2007, 2008, 2009  Free Software Foundation,
# Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.






pkgdatadir = $(datadir)/sane-backends
pkgincludedir = $(includedir)/sane-backends
pkglibdir = $(libdir)/sane-backends
pkglibexecdir = $(libexecdir)/sane-backends
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = i686-pc-linux-gnu
host_triplet = i686-pc-linux-gnu
bin_PROGRAMS = sane-find-scanner$(EXEEXT) gamma4scanimage$(EXEEXT)
noinst_PROGRAMS = sane-desc$(EXEEXT) umax_pp$(EXEEXT)
subdir = tools
DIST_COMMON = README $(srcdir)/Makefile.am $(srcdir)/Makefile.in \
	$(srcdir)/sane-backends.pc.in $(srcdir)/sane-config.in
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/acinclude.m4 \
	$(top_srcdir)/m4/libtool.m4 $(top_srcdir)/m4/byteorder.m4 \
	$(top_srcdir)/m4/stdint.m4 $(top_srcdir)/configure.in
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/include/sane/config.h
CONFIG_CLEAN_FILES = sane-config sane-backends.pc
CONFIG_CLEAN_VPATH_FILES =
am__installdirs = "$(DESTDIR)$(bindir)" "$(DESTDIR)$(bindir)" \
	"$(DESTDIR)$(pkgconfigdir)"
PROGRAMS = $(bin_PROGRAMS) $(noinst_PROGRAMS)
am_gamma4scanimage_OBJECTS = gamma4scanimage.$(OBJEXT)
gamma4scanimage_OBJECTS = $(am_gamma4scanimage_OBJECTS)
gamma4scanimage_DEPENDENCIES =
am_sane_desc_OBJECTS = sane-desc.$(OBJEXT)
sane_desc_OBJECTS = $(am_sane_desc_OBJECTS)
sane_desc_DEPENDENCIES = ../sanei/libsanei.la ../lib/liblib.la
am_sane_find_scanner_OBJECTS = sane-find-scanner.$(OBJEXT) \
	check-usb-chip.$(OBJEXT) sane_strstatus.$(OBJEXT)
sane_find_scanner_OBJECTS = $(am_sane_find_scanner_OBJECTS)
sane_find_scanner_DEPENDENCIES = ../sanei/libsanei.la ../lib/liblib.la
am_umax_pp_OBJECTS = umax_pp-umax_pp.$(OBJEXT) \
	umax_pp-umax_pp_low.$(OBJEXT)
umax_pp_OBJECTS = $(am_umax_pp_OBJECTS)
umax_pp_DEPENDENCIES = ../sanei/libsanei.la ../lib/liblib.la
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
SCRIPTS = $(bin_SCRIPTS) $(noinst_SCRIPTS)
DEFAULT_INCLUDES = -I. -I$(top_builddir)/include/sane
depcomp = $(SHELL) $(top_srcdir)/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
LTCOMPILE = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) \
	--mode=compile $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(LIBTOOL) --tag=CC $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) \
	--mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) \
	$(LDFLAGS) -o $@
SOURCES = $(gamma4scanimage_SOURCES) $(sane_desc_SOURCES) \
	$(sane_find_scanner_SOURCES) $(umax_pp_SOURCES)
DIST_SOURCES = $(gamma4scanimage_SOURCES) $(sane_desc_SOURCES) \
	$(sane_find_scanner_SOURCES) $(umax_pp_SOURCES)
DATA = $(pkgconfig_DATA)
ETAGS = etags
CTAGS = ctags
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /source/sane-backends-1.0.23/missing --run aclocal-1.11
ALLOCA = 
AMTAR = ${SHELL} /source/sane-backends-1.0.23/missing --run tar
AR = ar
AS = as
AUTOCONF = ${SHELL} /source/sane-backends-1.0.23/missing --run autoconf
AUTOHEADER = ${SHELL} /source/sane-backends-1.0.23/missing --run autoheader
AUTOMAKE = ${SHELL} /source/sane-backends-1.0.23/missing --run automake-1.11
AVAHI_CFLAGS = 
AVAHI_LIBS = 
AWK = gawk
BACKENDS =  abaton agfafocus apple artec artec_eplus48u as6e avision bh canon canon630u canon_dr cardscan coolscan coolscan2 coolscan3 dc25 dc210 dc240 dell1600n_net dmc epjitsu epson epson2 fujitsu genesys gt68xx hp hp3500 hp3900 hp4200 hp5400 hp5590 hpljm1005 hs2p ibm kodak kodakaio kvs1025 kvs20xx leo lexmark ma1509 magicolor matsushita microtek microtek2 mustek mustek_usb nec net niash pie pixma plustek plustek_pp qcam ricoh rts8891 s9036 sceptre sharp sm3600 sm3840 snapscan sp15c st400 stv680 tamarack teco1 teco2 teco3 test u12 umax umax_pp umax1220u xerox_mfp p5
BACKEND_CONFS_ENABLED =  abaton.conf agfafocus.conf apple.conf artec.conf artec_eplus48u.conf as6e.conf avision.conf bh.conf canon.conf canon630u.conf canon_dr.conf cardscan.conf coolscan.conf coolscan2.conf coolscan3.conf dc25.conf dc210.conf dc240.conf dell1600n_net.conf dmc.conf epjitsu.conf epson.conf epson2.conf fujitsu.conf genesys.conf gt68xx.conf hp.conf hp3500.conf hp3900.conf hp4200.conf hp5400.conf hp5590.conf hpljm1005.conf hs2p.conf ibm.conf kodak.conf kodakaio.conf kvs1025.conf kvs20xx.conf leo.conf lexmark.conf ma1509.conf magicolor.conf matsushita.conf microtek.conf microtek2.conf mustek.conf mustek_usb.conf nec.conf net.conf niash.conf pie.conf pixma.conf plustek.conf plustek_pp.conf qcam.conf ricoh.conf rts8891.conf s9036.conf sceptre.conf sharp.conf sm3600.conf sm3840.conf snapscan.conf sp15c.conf st400.conf stv680.conf tamarack.conf teco1.conf teco2.conf teco3.conf test.conf u12.conf umax.conf umax_pp.conf umax1220u.conf xerox_mfp.conf p5.conf
BACKEND_LIBS_ENABLED =  libsane-abaton.la libsane-agfafocus.la libsane-apple.la libsane-artec.la libsane-artec_eplus48u.la libsane-as6e.la libsane-avision.la libsane-bh.la libsane-canon.la libsane-canon630u.la libsane-canon_dr.la libsane-cardscan.la libsane-coolscan.la libsane-coolscan2.la libsane-coolscan3.la libsane-dc25.la libsane-dc210.la libsane-dc240.la libsane-dell1600n_net.la libsane-dmc.la libsane-epjitsu.la libsane-epson.la libsane-epson2.la libsane-fujitsu.la libsane-genesys.la libsane-gt68xx.la libsane-hp.la libsane-hp3500.la libsane-hp3900.la libsane-hp4200.la libsane-hp5400.la libsane-hp5590.la libsane-hpljm1005.la libsane-hs2p.la libsane-ibm.la libsane-kodak.la libsane-kodakaio.la libsane-kvs1025.la libsane-kvs20xx.la libsane-leo.la libsane-lexmark.la libsane-ma1509.la libsane-magicolor.la libsane-matsushita.la libsane-microtek.la libsane-microtek2.la libsane-mustek.la libsane-mustek_usb.la libsane-nec.la libsane-net.la libsane-niash.la libsane-pie.la libsane-pixma.la libsane-plustek.la libsane-plustek_pp.la libsane-qcam.la libsane-ricoh.la libsane-rts8891.la libsane-s9036.la libsane-sceptre.la libsane-sharp.la libsane-sm3600.la libsane-sm3840.la libsane-snapscan.la libsane-sp15c.la libsane-st400.la libsane-stv680.la libsane-tamarack.la libsane-teco1.la libsane-teco2.la libsane-teco3.la libsane-test.la libsane-u12.la libsane-umax.la libsane-umax_pp.la libsane-umax1220u.la libsane-xerox_mfp.la libsane-p5.la
BACKEND_MANS_ENABLED =  sane-abaton.5 sane-agfafocus.5 sane-apple.5 sane-artec.5 sane-artec_eplus48u.5 sane-as6e.5 sane-avision.5 sane-bh.5 sane-canon.5 sane-canon630u.5 sane-canon_dr.5 sane-cardscan.5 sane-coolscan.5 sane-coolscan2.5 sane-coolscan3.5 sane-dc25.5 sane-dc210.5 sane-dc240.5 sane-dell1600n_net.5 sane-dmc.5 sane-epjitsu.5 sane-epson.5 sane-epson2.5 sane-fujitsu.5 sane-genesys.5 sane-gt68xx.5 sane-hp.5 sane-hp3500.5 sane-hp3900.5 sane-hp4200.5 sane-hp5400.5 sane-hp5590.5 sane-hpljm1005.5 sane-hs2p.5 sane-ibm.5 sane-kodak.5 sane-kodakaio.5 sane-kvs1025.5 sane-kvs20xx.5 sane-leo.5 sane-lexmark.5 sane-ma1509.5 sane-magicolor.5 sane-matsushita.5 sane-microtek.5 sane-microtek2.5 sane-mustek.5 sane-mustek_usb.5 sane-nec.5 sane-net.5 sane-niash.5 sane-pie.5 sane-pixma.5 sane-plustek.5 sane-plustek_pp.5 sane-qcam.5 sane-ricoh.5 sane-rts8891.5 sane-s9036.5 sane-sceptre.5 sane-sharp.5 sane-sm3600.5 sane-sm3840.5 sane-snapscan.5 sane-sp15c.5 sane-st400.5 sane-stv680.5 sane-tamarack.5 sane-teco1.5 sane-teco2.5 sane-teco3.5 sane-test.5 sane-u12.5 sane-umax.5 sane-umax_pp.5 sane-umax1220u.5 sane-xerox_mfp.5 sane-p5.5
CC = i486-TSOL-linux-gnu-gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -Os -W -Wall -I/usr/include/libusb-1.0  
CPP = i486-TSOL-linux-gnu-gcc -E
CPPFLAGS =  -DPATH_SANE_CONFIG_DIR=$(configdir) 	  -DPATH_SANE_DATA_DIR=$(datadir) 	  -DPATH_SANE_LOCK_DIR=$(locksanedir) 	  -DV_MAJOR=1 -DV_MINOR=0
CYGPATH_W = echo
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DISTCLEAN_FILES = *~ .*~ *.log *.bak *.old *.orig *.out *.rej "\#"* ".\#"*
DLLTOOL = dlltool
DL_LIBS = -ldl
DSYMUTIL = 
DUMPBIN = 
DVIPS = no
DYNAMIC_FLAG = -module
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /usr/bin/grep -E
EXEEXT = 
FGREP = /usr/bin/grep -F
GPHOTO2_CPPFLAGS = 
GPHOTO2_LDFLAGS = 
GPHOTO2_LIBS = 
GREP = /usr/bin/grep
HAVE_GPHOTO2 = false
IEEE1284_LIBS = 
INCLUDES =  -I/usr/local/include
INSTALL = /bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_LOCKPATH = 
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
JPEG_LIBS = -ljpeg
LATEX = no
LD = i486-TSOL-linux-gnu-ld
LDFLAGS = -static-libgcc
LIBOBJS = 
LIBS = 
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIBUSB_1_0_CFLAGS = -I/usr/include/libusb-1.0  
LIBUSB_1_0_LIBS = -lusb-1.0  
LIBV4L_CFLAGS = 
LIBV4L_LIBS = 
LINKER_RPATH = -Wl,-rpath,
LIPO = 
LN_S = ln -s
LOCKPATH_GROUP = uucp
LTLIBOBJS = 
MAINT = #
MAKEINDEX = no
MAKEINFO = ${SHELL} /source/sane-backends-1.0.23/missing --run makeinfo
MANIFEST_TOOL = :
MATH_LIB = -lm
MKDIR_P = /bin/mkdir -p
MSGFMT = /usr/bin/msgfmt
MSGMERGE = /usr/bin/msgmerge
NM = /toolchain/i486-TSOL-linux-gnu/bin//nm -B
NMEDIT = 
NUMBER_VERSION = 1.0.23
OBJDUMP = objdump
OBJEXT = o
OTOOL = 
OTOOL64 = 
PACKAGE = sane-backends
PACKAGE_BUGREPORT = sane-devel@lists.alioth.debian.org
PACKAGE_NAME = sane-backends
PACKAGE_STRING = sane-backends 1.0.23
PACKAGE_TARNAME = sane-backends
PACKAGE_URL = 
PACKAGE_VERSION = 1.0.23
PATH_SEPARATOR = :
PKG_CONFIG = /usr/bin/pkg-config
PKG_CONFIG_LIBDIR = 
PKG_CONFIG_PATH = /usr/xorg/lib/pkgconfig:/usr/xorg/share/pkgconfig:
PRELOADABLE_BACKENDS = 
PRELOADABLE_BACKENDS_ENABLED = 
PTHREAD_LIBS = 
RANLIB = ranlib
RESMGR_LIBS = 
SANEI_SANEI_JPEG_LO = ../sanei/sanei_jpeg.lo
SANE_CONFIG_PATH = no
SCSI_LIBS = 
SED = /usr/bin/sed
SET_MAKE = 
SHELL = /bin/sh
SNMP_CONFIG_PATH = no
SOCKET_LIBS =    
STRICT_LDFLAGS = -Wl,-z,defs
STRIP = strip
SYSLOG_LIBS = 
TIFF_LIBS = -ltiff
USB_LIBS =  -lusb-1.0  
VERSION = 1.0.23
V_MAJOR = 1
V_MINOR = 0
V_REV = 23
XGETTEXT = /usr/bin/xgettext
abs_builddir = /source/sane-backends-1.0.23/tools
abs_srcdir = /source/sane-backends-1.0.23/tools
abs_top_builddir = /source/sane-backends-1.0.23
abs_top_srcdir = /source/sane-backends-1.0.23
ac_ct_AR = ar
ac_ct_CC = i486-TSOL-linux-gnu-gcc
ac_ct_DUMPBIN = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = ${AMTAR} chof - "$$tardir"
am__untar = ${AMTAR} xf -
bindir = ${exec_prefix}/bin
build = i686-pc-linux-gnu
build_alias = 
build_cpu = i686
build_os = linux-gnu
build_vendor = pc
builddir = .
configdir = ${prefix}/etc/sane.d
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${prefix}/doc/sane-${VERSION}
dvidir = ${docdir}
effective_target = i686-pc-linux-gnu
exec_prefix = ${prefix}
host = i686-pc-linux-gnu
host_alias = 
host_cpu = i686
host_os = linux-gnu
host_vendor = pc
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /source/sane-backends-1.0.23/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
locksanedir = ${prefix}/var/lock/sane
mandir = ${datarootdir}/man
mkdir_p = /bin/mkdir -p
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr
program_transform_name = s,x,x,
psdir = ${docdir}
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../
top_builddir = ..
top_srcdir = ..
AM_CPPFLAGS = -I. -I$(srcdir) -I$(top_builddir)/include \
 -I$(top_srcdir)/include

HOTPLUG = hal/libsane.fdi hotplug/libsane.usermap hotplug-ng/libsane.db \
	  udev/libsane.rules

#HOTPLUG = 
HOTPLUG_DIRS = hal hotplug hotplug-ng udev
#HOTPLUG_DIRS = 
HOTPLUG_DIR = dirs
#HOTPLUG_DIR = 
bin_SCRIPTS = sane-config
noinst_SCRIPTS = $(HOTPLUG)
BUILT_SOURCES = $(HOTPLUG_DIR)
CLEANFILES = $(bin_SCRIPTS) $(dist_noinst_SCRIPTS)
EXTRA_DIST = check-po.awk libtool-get-dll-ext mustek600iin-off.c \
	RenSaneDlls.cmd README xerox hotplug/README \
	hotplug/libusbscanner hotplug-ng/README \
	hotplug-ng/libsane.hotplug openbsd/attach openbsd/detach
sane_find_scanner_SOURCES = sane-find-scanner.c check-usb-chip.c \
			    ../backend/sane_strstatus.c

sane_find_scanner_LDADD = ../sanei/libsanei.la ../lib/liblib.la \
			   -lusb-1.0    

gamma4scanimage_SOURCES = gamma4scanimage.c
gamma4scanimage_LDADD = -lm
umax_pp_SOURCES = umax_pp.c ../backend/umax_pp_low.c
umax_pp_CPPFLAGS = $(AM_CPPFLAGS) -DBACKEND_NAME=umax_pp_low
umax_pp_LDADD = ../sanei/libsanei.la ../lib/liblib.la -lm
sane_desc_SOURCES = sane-desc.c
sane_desc_LDADD = ../sanei/libsanei.la ../lib/liblib.la
pkgconfigdir = ${exec_prefix}/lib/pkgconfig
pkgconfig_DATA = sane-backends.pc
all: $(BUILT_SOURCES)
	$(MAKE) $(AM_MAKEFLAGS) all-am

.SUFFIXES:
.SUFFIXES: .c .lo .o .obj
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --gnu tools/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --gnu tools/Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure: # $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4): # $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
sane-config: $(top_builddir)/config.status $(srcdir)/sane-config.in
	cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@
sane-backends.pc: $(top_builddir)/config.status $(srcdir)/sane-backends.pc.in
	cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@
install-binPROGRAMS: $(bin_PROGRAMS)
	@$(NORMAL_INSTALL)
	test -z "$(bindir)" || $(MKDIR_P) "$(DESTDIR)$(bindir)"
	@list='$(bin_PROGRAMS)'; test -n "$(bindir)" || list=; \
	for p in $$list; do echo "$$p $$p"; done | \
	sed 's/$(EXEEXT)$$//' | \
	while read p p1; do if test -f $$p || test -f $$p1; \
	  then echo "$$p"; echo "$$p"; else :; fi; \
	done | \
	sed -e 'p;s,.*/,,;n;h' -e 's|.*|.|' \
	    -e 'p;x;s,.*/,,;s/$(EXEEXT)$$//;$(transform);s/$$/$(EXEEXT)/' | \
	sed 'N;N;N;s,\n, ,g' | \
	$(AWK) 'BEGIN { files["."] = ""; dirs["."] = 1 } \
	  { d=$$3; if (dirs[d] != 1) { print "d", d; dirs[d] = 1 } \
	    if ($$2 == $$4) files[d] = files[d] " " $$1; \
	    else { print "f", $$3 "/" $$4, $$1; } } \
	  END { for (d in files) print "f", d, files[d] }' | \
	while read type dir files; do \
	    if test "$$dir" = .; then dir=; else dir=/$$dir; fi; \
	    test -z "$$files" || { \
	    echo " $(INSTALL_PROGRAM_ENV) $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL_PROGRAM) $$files '$(DESTDIR)$(bindir)$$dir'"; \
	    $(INSTALL_PROGRAM_ENV) $(LIBTOOL) $(AM_LIBTOOLFLAGS) $(LIBTOOLFLAGS) --mode=install $(INSTALL_PROGRAM) $$files "$(DESTDIR)$(bindir)$$dir" || exit $$?; \
	    } \
	; done

uninstall-binPROGRAMS:
	@$(NORMAL_UNINSTALL)
	@list='$(bin_PROGRAMS)'; test -n "$(bindir)" || list=; \
	files=`for p in $$list; do echo "$$p"; done | \
	  sed -e 'h;s,^.*/,,;s/$(EXEEXT)$$//;$(transform)' \
	      -e 's/$$/$(EXEEXT)/' `; \
	test -n "$$list" || exit 0; \
	echo " ( cd '$(DESTDIR)$(bindir)' && rm -f" $$files ")"; \
	cd "$(DESTDIR)$(bindir)" && rm -f $$files

clean-binPROGRAMS:
	@list='$(bin_PROGRAMS)'; test -n "$$list" || exit 0; \
	echo " rm -f" $$list; \
	rm -f $$list || exit $$?; \
	test -n "$(EXEEXT)" || exit 0; \
	list=`for p in $$list; do echo "$$p"; done | sed 's/$(EXEEXT)$$//'`; \
	echo " rm -f" $$list; \
	rm -f $$list

clean-noinstPROGRAMS:
	@list='$(noinst_PROGRAMS)'; test -n "$$list" || exit 0; \
	echo " rm -f" $$list; \
	rm -f $$list || exit $$?; \
	test -n "$(EXEEXT)" || exit 0; \
	list=`for p in $$list; do echo "$$p"; done | sed 's/$(EXEEXT)$$//'`; \
	echo " rm -f" $$list; \
	rm -f $$list
gamma4scanimage$(EXEEXT): $(gamma4scanimage_OBJECTS) $(gamma4scanimage_DEPENDENCIES) 
	@rm -f gamma4scanimage$(EXEEXT)
	$(LINK) $(gamma4scanimage_OBJECTS) $(gamma4scanimage_LDADD) $(LIBS)
sane-desc$(EXEEXT): $(sane_desc_OBJECTS) $(sane_desc_DEPENDENCIES) 
	@rm -f sane-desc$(EXEEXT)
	$(LINK) $(sane_desc_OBJECTS) $(sane_desc_LDADD) $(LIBS)
sane-find-scanner$(EXEEXT): $(sane_find_scanner_OBJECTS) $(sane_find_scanner_DEPENDENCIES) 
	@rm -f sane-find-scanner$(EXEEXT)
	$(LINK) $(sane_find_scanner_OBJECTS) $(sane_find_scanner_LDADD) $(LIBS)
umax_pp$(EXEEXT): $(umax_pp_OBJECTS) $(umax_pp_DEPENDENCIES) 
	@rm -f umax_pp$(EXEEXT)
	$(LINK) $(umax_pp_OBJECTS) $(umax_pp_LDADD) $(LIBS)
install-binSCRIPTS: $(bin_SCRIPTS)
	@$(NORMAL_INSTALL)
	test -z "$(bindir)" || $(MKDIR_P) "$(DESTDIR)$(bindir)"
	@list='$(bin_SCRIPTS)'; test -n "$(bindir)" || list=; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  if test -f "$$d$$p"; then echo "$$d$$p"; echo "$$p"; else :; fi; \
	done | \
	sed -e 'p;s,.*/,,;n' \
	    -e 'h;s|.*|.|' \
	    -e 'p;x;s,.*/,,;$(transform)' | sed 'N;N;N;s,\n, ,g' | \
	$(AWK) 'BEGIN { files["."] = ""; dirs["."] = 1; } \
	  { d=$$3; if (dirs[d] != 1) { print "d", d; dirs[d] = 1 } \
	    if ($$2 == $$4) { files[d] = files[d] " " $$1; \
	      if (++n[d] == $(am__install_max)) { \
		print "f", d, files[d]; n[d] = 0; files[d] = "" } } \
	    else { print "f", d "/" $$4, $$1 } } \
	  END { for (d in files) print "f", d, files[d] }' | \
	while read type dir files; do \
	     if test "$$dir" = .; then dir=; else dir=/$$dir; fi; \
	     test -z "$$files" || { \
	       echo " $(INSTALL_SCRIPT) $$files '$(DESTDIR)$(bindir)$$dir'"; \
	       $(INSTALL_SCRIPT) $$files "$(DESTDIR)$(bindir)$$dir" || exit $$?; \
	     } \
	; done

uninstall-binSCRIPTS:
	@$(NORMAL_UNINSTALL)
	@list='$(bin_SCRIPTS)'; test -n "$(bindir)" || exit 0; \
	files=`for p in $$list; do echo "$$p"; done | \
	       sed -e 's,.*/,,;$(transform)'`; \
	test -n "$$list" || exit 0; \
	echo " ( cd '$(DESTDIR)$(bindir)' && rm -f" $$files ")"; \
	cd "$(DESTDIR)$(bindir)" && rm -f $$files

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/check-usb-chip.Po
include ./$(DEPDIR)/gamma4scanimage.Po
include ./$(DEPDIR)/sane-desc.Po
include ./$(DEPDIR)/sane-find-scanner.Po
include ./$(DEPDIR)/sane_strstatus.Po
include ./$(DEPDIR)/umax_pp-umax_pp.Po
include ./$(DEPDIR)/umax_pp-umax_pp_low.Po

.c.o:
	$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(COMPILE) -c $<

.c.obj:
	$(COMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(COMPILE) -c `$(CYGPATH_W) '$<'`

.c.lo:
	$(LTCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Plo
#	source='$<' object='$@' libtool=yes \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(LTCOMPILE) -c -o $@ $<

sane_strstatus.o: ../backend/sane_strstatus.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS) -MT sane_strstatus.o -MD -MP -MF $(DEPDIR)/sane_strstatus.Tpo -c -o sane_strstatus.o `test -f '../backend/sane_strstatus.c' || echo '$(srcdir)/'`../backend/sane_strstatus.c
	$(am__mv) $(DEPDIR)/sane_strstatus.Tpo $(DEPDIR)/sane_strstatus.Po
#	source='../backend/sane_strstatus.c' object='sane_strstatus.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS) -c -o sane_strstatus.o `test -f '../backend/sane_strstatus.c' || echo '$(srcdir)/'`../backend/sane_strstatus.c

sane_strstatus.obj: ../backend/sane_strstatus.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS) -MT sane_strstatus.obj -MD -MP -MF $(DEPDIR)/sane_strstatus.Tpo -c -o sane_strstatus.obj `if test -f '../backend/sane_strstatus.c'; then $(CYGPATH_W) '../backend/sane_strstatus.c'; else $(CYGPATH_W) '$(srcdir)/../backend/sane_strstatus.c'; fi`
	$(am__mv) $(DEPDIR)/sane_strstatus.Tpo $(DEPDIR)/sane_strstatus.Po
#	source='../backend/sane_strstatus.c' object='sane_strstatus.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS) -c -o sane_strstatus.obj `if test -f '../backend/sane_strstatus.c'; then $(CYGPATH_W) '../backend/sane_strstatus.c'; else $(CYGPATH_W) '$(srcdir)/../backend/sane_strstatus.c'; fi`

umax_pp-umax_pp.o: umax_pp.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(umax_pp_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS) -MT umax_pp-umax_pp.o -MD -MP -MF $(DEPDIR)/umax_pp-umax_pp.Tpo -c -o umax_pp-umax_pp.o `test -f 'umax_pp.c' || echo '$(srcdir)/'`umax_pp.c
	$(am__mv) $(DEPDIR)/umax_pp-umax_pp.Tpo $(DEPDIR)/umax_pp-umax_pp.Po
#	source='umax_pp.c' object='umax_pp-umax_pp.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(umax_pp_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS) -c -o umax_pp-umax_pp.o `test -f 'umax_pp.c' || echo '$(srcdir)/'`umax_pp.c

umax_pp-umax_pp.obj: umax_pp.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(umax_pp_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS) -MT umax_pp-umax_pp.obj -MD -MP -MF $(DEPDIR)/umax_pp-umax_pp.Tpo -c -o umax_pp-umax_pp.obj `if test -f 'umax_pp.c'; then $(CYGPATH_W) 'umax_pp.c'; else $(CYGPATH_W) '$(srcdir)/umax_pp.c'; fi`
	$(am__mv) $(DEPDIR)/umax_pp-umax_pp.Tpo $(DEPDIR)/umax_pp-umax_pp.Po
#	source='umax_pp.c' object='umax_pp-umax_pp.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(umax_pp_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS) -c -o umax_pp-umax_pp.obj `if test -f 'umax_pp.c'; then $(CYGPATH_W) 'umax_pp.c'; else $(CYGPATH_W) '$(srcdir)/umax_pp.c'; fi`

umax_pp-umax_pp_low.o: ../backend/umax_pp_low.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(umax_pp_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS) -MT umax_pp-umax_pp_low.o -MD -MP -MF $(DEPDIR)/umax_pp-umax_pp_low.Tpo -c -o umax_pp-umax_pp_low.o `test -f '../backend/umax_pp_low.c' || echo '$(srcdir)/'`../backend/umax_pp_low.c
	$(am__mv) $(DEPDIR)/umax_pp-umax_pp_low.Tpo $(DEPDIR)/umax_pp-umax_pp_low.Po
#	source='../backend/umax_pp_low.c' object='umax_pp-umax_pp_low.o' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(umax_pp_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS) -c -o umax_pp-umax_pp_low.o `test -f '../backend/umax_pp_low.c' || echo '$(srcdir)/'`../backend/umax_pp_low.c

umax_pp-umax_pp_low.obj: ../backend/umax_pp_low.c
	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(umax_pp_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS) -MT umax_pp-umax_pp_low.obj -MD -MP -MF $(DEPDIR)/umax_pp-umax_pp_low.Tpo -c -o umax_pp-umax_pp_low.obj `if test -f '../backend/umax_pp_low.c'; then $(CYGPATH_W) '../backend/umax_pp_low.c'; else $(CYGPATH_W) '$(srcdir)/../backend/umax_pp_low.c'; fi`
	$(am__mv) $(DEPDIR)/umax_pp-umax_pp_low.Tpo $(DEPDIR)/umax_pp-umax_pp_low.Po
#	source='../backend/umax_pp_low.c' object='umax_pp-umax_pp_low.obj' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(umax_pp_CPPFLAGS) $(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS) -c -o umax_pp-umax_pp_low.obj `if test -f '../backend/umax_pp_low.c'; then $(CYGPATH_W) '../backend/umax_pp_low.c'; else $(CYGPATH_W) '$(srcdir)/../backend/umax_pp_low.c'; fi`

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs
install-pkgconfigDATA: $(pkgconfig_DATA)
	@$(NORMAL_INSTALL)
	test -z "$(pkgconfigdir)" || $(MKDIR_P) "$(DESTDIR)$(pkgconfigdir)"
	@list='$(pkgconfig_DATA)'; test -n "$(pkgconfigdir)" || list=; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(pkgconfigdir)'"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(pkgconfigdir)" || exit $$?; \
	done

uninstall-pkgconfigDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(pkgconfig_DATA)'; test -n "$(pkgconfigdir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	test -n "$$files" || exit 0; \
	echo " ( cd '$(DESTDIR)$(pkgconfigdir)' && rm -f" $$files ")"; \
	cd "$(DESTDIR)$(pkgconfigdir)" && rm -f $$files

ID: $(HEADERS) $(SOURCES) $(LISP) $(TAGS_FILES)
	list='$(SOURCES) $(HEADERS) $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	mkid -fID $$unique
tags: TAGS

TAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	set x; \
	here=`pwd`; \
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: CTAGS
CTAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '{ files[$$0] = 1; nonempty = 1; } \
	      END { if (nonempty) { for (i in files) print i; }; }'`; \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: $(BUILT_SOURCES)
	$(MAKE) $(AM_MAKEFLAGS) check-am
all-am: Makefile $(PROGRAMS) $(SCRIPTS) $(DATA)
installdirs:
	for dir in "$(DESTDIR)$(bindir)" "$(DESTDIR)$(bindir)" "$(DESTDIR)$(pkgconfigdir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: $(BUILT_SOURCES)
	$(MAKE) $(AM_MAKEFLAGS) install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	  install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	  `test -z '$(STRIP)' || \
	    echo "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'"` install
mostlyclean-generic:

clean-generic:
	-test -z "$(CLEANFILES)" || rm -f $(CLEANFILES)

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
	-test -z "$(BUILT_SOURCES)" || rm -f $(BUILT_SOURCES)
clean: clean-am

clean-am: clean-binPROGRAMS clean-generic clean-libtool clean-local \
	clean-noinstPROGRAMS mostlyclean-am

distclean: distclean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am: install-pkgconfigDATA

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am: install-binPROGRAMS install-binSCRIPTS

install-html: install-html-am

install-html-am:

install-info: install-info-am

install-info-am:

install-man:

install-pdf: install-pdf-am

install-pdf-am:

install-ps: install-ps-am

install-ps-am:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-binPROGRAMS uninstall-binSCRIPTS \
	uninstall-pkgconfigDATA

.MAKE: all check install install-am install-strip

.PHONY: CTAGS GTAGS all all-am check check-am clean clean-binPROGRAMS \
	clean-generic clean-libtool clean-local clean-noinstPROGRAMS \
	ctags distclean distclean-compile distclean-generic \
	distclean-libtool distclean-tags distdir dvi dvi-am html \
	html-am info info-am install install-am install-binPROGRAMS \
	install-binSCRIPTS install-data install-data-am install-dvi \
	install-dvi-am install-exec install-exec-am install-html \
	install-html-am install-info install-info-am install-man \
	install-pdf install-pdf-am install-pkgconfigDATA install-ps \
	install-ps-am install-strip installcheck installcheck-am \
	installdirs maintainer-clean maintainer-clean-generic \
	mostlyclean mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool pdf pdf-am ps ps-am tags uninstall \
	uninstall-am uninstall-binPROGRAMS uninstall-binSCRIPTS \
	uninstall-pkgconfigDATA


# When build directory is not same as source directory then any
# subdirectories that targets use must be manually created (under
# the build directory that is).
dirs:
	for subdir in $(HOTPLUG_DIRS); do \
	  $(MKDIR_P) $$subdir || exit 1; \
	  done

hotplug/libsane.usermap: $(wildcard ${top_srcdir}/doc/descriptions/*.desc) $(wildcard ${top_srcdir}/doc/descriptions-external/*.desc) sane-desc
	@./sane-desc -m usermap -s ${top_srcdir}/doc/descriptions:${top_srcdir}/doc/descriptions-external \
	   -d 1 > $@

hotplug-ng/libsane.db: $(wildcard ${top_srcdir}/doc/descriptions/*.desc) $(wildcard ${top_srcdir}/doc/descriptions-external/*.desc) sane-desc
	@./sane-desc -m db -s ${top_srcdir}/doc/descriptions:${top_srcdir}/doc/descriptions-external \
	   -d 0 > $@

udev/libsane.rules: $(wildcard ${top_srcdir}/doc/descriptions/*.desc) $(wildcard ${top_srcdir}/doc/descriptions-external/*.desc) sane-desc
	@./sane-desc -m udev -s ${top_srcdir}/doc/descriptions:${top_srcdir}/doc/descriptions-external \
	   -d 0 > $@

hal/libsane.fdi: $(wildcard ${top_srcdir}/doc/descriptions/*.desc) $(wildcard ${top_srcdir}/doc/descriptions-external/*.desc) sane-desc
	@./sane-desc -m hal -s ${top_srcdir}/doc/descriptions:${top_srcdir}/doc/descriptions-external \
	   -d 0 > $@

clean-local:
	rm -f $(HOTPLUG)

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
