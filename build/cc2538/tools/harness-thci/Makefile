# Makefile.in generated by automake 1.15 from Makefile.am.
# tools/harness-thci/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994-2014 Free Software Foundation, Inc.

# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.



#
#  Copyright (c) 2016, The OpenThread Authors.
#  All rights reserved.
#
#  Redistribution and use in source and binary forms, with or without
#  modification, are permitted provided that the following conditions are met:
#  1. Redistributions of source code must retain the above copyright
#     notice, this list of conditions and the following disclaimer.
#  2. Redistributions in binary form must reproduce the above copyright
#     notice, this list of conditions and the following disclaimer in the
#     documentation and/or other materials provided with the distribution.
#  3. Neither the name of the copyright holder nor the
#     names of its contributors may be used to endorse or promote products
#     derived from this software without specific prior written permission.
#
#  THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
#  AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
#  IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
#  ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE
#  LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
#  CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
#  SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
#  INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
#  CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
#  ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
#  POSSIBILITY OF SUCH DAMAGE.
#
VPATH = /home/tri/openthread/examples/../tools/harness-thci
am__is_gnu_make = { \
  if test -z '$(MAKELEVEL)'; then \
    false; \
  elif test -n '$(MAKE_HOST)'; then \
    true; \
  elif test -n '$(MAKE_VERSION)' && test -n '$(CURDIR)'; then \
    true; \
  else \
    false; \
  fi; \
}
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/openthread
pkgincludedir = $(includedir)/openthread
pkglibdir = $(libdir)/openthread
pkglibexecdir = $(libexecdir)/openthread
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
build_triplet = x86_64-unknown-linux-gnu
host_triplet = arm-none-eabi
subdir = tools/harness-thci
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/third_party/nlbuild-autotools/repo/autoconf/m4/ax_check_compiler.m4 \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/autoconf/m4/nl_enable_coverage.m4 \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/autoconf/m4/nl_enable_coverage_reporting.m4 \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/autoconf/m4/nl_enable_debug.m4 \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/autoconf/m4/nl_enable_docs.m4 \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/autoconf/m4/nl_enable_optimization.m4 \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/autoconf/m4/nl_enable_tests.m4 \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/autoconf/m4/nl_filtered_canonical.m4 \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/autoconf/m4/nl_werror.m4 \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/third_party/autoconf/m4/libtool.m4 \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/third_party/autoconf/m4/ltoptions.m4 \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/third_party/autoconf/m4/ltsugar.m4 \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/third_party/autoconf/m4/ltversion.m4 \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/third_party/autoconf/m4/lt~obsolete.m4 \
	$(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
DIST_COMMON = $(srcdir)/Makefile.am $(am__DIST_COMMON)
mkinstalldirs = $(SHELL) \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/third_party/autoconf/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/include/openthread-config-generic.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
AM_V_P = $(am__v_P_$(V))
am__v_P_ = $(am__v_P_$(AM_DEFAULT_VERBOSITY))
am__v_P_0 = false
am__v_P_1 = :
AM_V_GEN = $(am__v_GEN_$(V))
am__v_GEN_ = $(am__v_GEN_$(AM_DEFAULT_VERBOSITY))
am__v_GEN_0 = @echo "  GEN     " $@;
am__v_GEN_1 = 
AM_V_at = $(am__v_at_$(V))
am__v_at_ = $(am__v_at_$(AM_DEFAULT_VERBOSITY))
am__v_at_0 = @
am__v_at_1 = 
SOURCES =
DIST_SOURCES =
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
am__DIST_COMMON = $(srcdir)/Makefile.in \
	$(top_srcdir)/third_party/nlbuild-autotools/repo/third_party/autoconf/mkinstalldirs
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /home/tri/openthread/third_party/nlbuild-autotools/repo/third_party/autoconf/missing aclocal-1.15
AMTAR = $${TAR-tar}
AM_DEFAULT_VERBOSITY = 0
AR = arm-none-eabi-ar
AUTOCONF = ${SHELL} /home/tri/openthread/third_party/nlbuild-autotools/repo/third_party/autoconf/missing autoconf
AUTOHEADER = ${SHELL} /home/tri/openthread/third_party/nlbuild-autotools/repo/third_party/autoconf/missing autoheader
AUTOMAKE = ${SHELL} /home/tri/openthread/third_party/nlbuild-autotools/repo/third_party/autoconf/missing automake-1.15
AWK = mawk
CC = arm-none-eabi-gcc
CCAS = arm-none-eabi-gcc
CCASDEPMODE = depmode=gcc3
CCASFLAGS =  -fdata-sections -ffunction-sections -Os -g -DOPENTHREAD_PROJECT_CORE_CONFIG_FILE='"openthread-core-cc2538-config.h"' -I/home/tri/openthread/examples/../examples/platforms/cc2538/  -mcpu=cortex-m3 -mfloat-abi=soft -mthumb 
CCDEPMODE = depmode=gcc3
CFLAGS =  -fdata-sections -ffunction-sections -Os -g -DOPENTHREAD_PROJECT_CORE_CONFIG_FILE='"openthread-core-cc2538-config.h"' -I/home/tri/openthread/examples/../examples/platforms/cc2538/  -mcpu=cortex-m3 -mfloat-abi=soft -mthumb  -Wall -Wextra -Wshadow -Werror -std=c99 -pedantic-errors -D_BSD_SOURCE=1 -D_DEFAULT_SOURCE=1
CMP = /usr/bin/cmp
CPP = arm-none-eabi-cpp
CPPFLAGS = -fdata-sections -ffunction-sections -Os -g -DOPENTHREAD_PROJECT_CORE_CONFIG_FILE='"openthread-core-cc2538-config.h"' -I/home/tri/openthread/examples/../examples/platforms/cc2538/  -mcpu=cortex-m3 -mfloat-abi=soft -mthumb  -I${abs_top_srcdir}/third_party/mbedtls -I${abs_top_srcdir}/third_party/mbedtls/repo/include -DMBEDTLS_CONFIG_FILE=\"mbedtls-config.h\" 
CXX = arm-none-eabi-g++
CXXCPP = arm-none-eabi-g++ -E
CXXDEPMODE = depmode=gcc3
CXXFLAGS =  -fdata-sections -ffunction-sections -Os -g -DOPENTHREAD_PROJECT_CORE_CONFIG_FILE='"openthread-core-cc2538-config.h"' -I/home/tri/openthread/examples/../examples/platforms/cc2538/  -mcpu=cortex-m3 -mfloat-abi=soft -mthumb -fno-exceptions -fno-rtti  -Wall -Wextra -Wshadow -Werror -std=gnu++98 -Wno-c++14-compat -fno-exceptions -fno-rtti -D_BSD_SOURCE=1 -D_DEFAULT_SOURCE=1
CYGPATH_W = echo
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DLLTOOL = false
DOT = 
DOXYGEN = 
DOXYGEN_USE_DOT = NO
DSYMUTIL = 
DUMPBIN = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = /bin/grep -E
EXEEXT = 
FGREP = /bin/grep -F
GENHTML = 
GREP = /bin/grep
INSTALL = /usr/bin/install -p
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
LCOV = 
LD = /usr/arm-none-eabi/bin/ld
LDFLAGS = -fdata-sections -ffunction-sections -Os -g -DOPENTHREAD_PROJECT_CORE_CONFIG_FILE='"openthread-core-cc2538-config.h"' -I/home/tri/openthread/examples/../examples/platforms/cc2538/  -mcpu=cortex-m3 -mfloat-abi=soft -mthumb -nostartfiles -specs=nano.specs -specs=nosys.specs -Wl,--gc-sections 
LIBOBJS = 
LIBOPENTHREAD_VERSION_AGE = 5
LIBOPENTHREAD_VERSION_CURRENT = 0
LIBOPENTHREAD_VERSION_INFO = 0:0:5
LIBOPENTHREAD_VERSION_REVISION = 0
LIBS =  
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LIPO = 
LN_S = ln -s
LTLIBOBJS = 
LT_SYS_LIBRARY_PATH = 
MAINT = #
MAKEINFO = ${SHELL} /home/tri/openthread/third_party/nlbuild-autotools/repo/third_party/autoconf/missing makeinfo
MANIFEST_TOOL = :
MKDIR_P = /bin/mkdir -p
NM = arm-none-eabi-nm
NMEDIT = 
OBJCOPY = arm-none-eabi-objcopy
OBJDUMP = arm-none-eabi-objdump
OBJEXT = o
OPENTHREAD_CUSTOM_LINKER_FILE = 
OPENTHREAD_ENABLE_APPLICATION_COAP = 0
OPENTHREAD_ENABLE_APPLICATION_COAP_SECURE = 0
OPENTHREAD_ENABLE_BORDER_AGENT = 0
OPENTHREAD_ENABLE_BORDER_ROUTER = 0
OPENTHREAD_ENABLE_CERT_LOG = 0
OPENTHREAD_ENABLE_CHANNEL_MANAGER = 0
OPENTHREAD_ENABLE_CHANNEL_MONITOR = 0
OPENTHREAD_ENABLE_CHILD_SUPERVISION = 0
OPENTHREAD_ENABLE_CLI = 1
OPENTHREAD_ENABLE_COMMISSIONER = 0
OPENTHREAD_ENABLE_DHCP6_CLIENT = 0
OPENTHREAD_ENABLE_DHCP6_SERVER = 0
OPENTHREAD_ENABLE_DIAG = 1
OPENTHREAD_ENABLE_DNS_CLIENT = 0
OPENTHREAD_ENABLE_DTLS = 0
OPENTHREAD_ENABLE_ECDSA = 0
OPENTHREAD_ENABLE_EXAMPLES = cc2538
OPENTHREAD_ENABLE_EXECUTABLE = 1
OPENTHREAD_ENABLE_FTD = 1
OPENTHREAD_ENABLE_JAM_DETECTION = 0
OPENTHREAD_ENABLE_JOINER = 0
OPENTHREAD_ENABLE_LEGACY = 0
OPENTHREAD_ENABLE_MAC_FILTER = 0
OPENTHREAD_ENABLE_MTD = 1
OPENTHREAD_ENABLE_MTD_NETWORK_DIAGNOSTIC = 0
OPENTHREAD_ENABLE_MULTIPLE_INSTANCES = 0
OPENTHREAD_ENABLE_NCP = 1
OPENTHREAD_ENABLE_NCP_SPI = 0
OPENTHREAD_ENABLE_NCP_UART = 1
OPENTHREAD_ENABLE_PLATFORM_NETIF = 0
OPENTHREAD_ENABLE_PLATFORM_UDP = 0
OPENTHREAD_ENABLE_POSIX_APP_DAEMON = 0
OPENTHREAD_ENABLE_RADIO_ONLY = 1
OPENTHREAD_ENABLE_RAW_LINK_API = 0
OPENTHREAD_ENABLE_SERVICE = 0
OPENTHREAD_ENABLE_SNTP_CLIENT = 0
OPENTHREAD_ENABLE_UDP_FORWARD = 0
OPENTHREAD_EXAMPLES_CC1352 = 
OPENTHREAD_EXAMPLES_CC2538 = 1
OPENTHREAD_EXAMPLES_CC2650 = 
OPENTHREAD_EXAMPLES_CC2652 = 
OPENTHREAD_EXAMPLES_DA15000 = 
OPENTHREAD_EXAMPLES_EFR32 = 
OPENTHREAD_EXAMPLES_EMSK = 
OPENTHREAD_EXAMPLES_GP712 = 
OPENTHREAD_EXAMPLES_KW41Z = 
OPENTHREAD_EXAMPLES_NRF52811 = 
OPENTHREAD_EXAMPLES_NRF52840 = 
OPENTHREAD_EXAMPLES_POSIX = 
OPENTHREAD_EXAMPLES_QPG6095 = 
OPENTHREAD_EXAMPLES_SAMR21 = 
OPENTHREAD_NCP_SPINEL_ENCRYPTER_LIBS = 
OPENTHREAD_NCP_VENDOR_HOOK_SOURCE = 
OPENTHREAD_PLATFORM_POSIX_APP = 0
OPENTHREAD_TARGET_DARWIN = 
OPENTHREAD_TARGET_DEFINES = 
OPENTHREAD_TARGET_LINUX = 
OPENTHREAD_VENDOR_EXTENSION_SOURCE = 
OTOOL = 
OTOOL64 = 
PACKAGE = openthread
PACKAGE_BUGREPORT = openthread-devel@googlegroups.com
PACKAGE_NAME = OPENTHREAD
PACKAGE_STRING = OPENTHREAD 20180926-00440-gbf794ca-dirty
PACKAGE_TARNAME = openthread
PACKAGE_URL = http://github.com/openthread/openthread
PACKAGE_VERSION = 20180926-00440-gbf794ca-dirty
PATH_SEPARATOR = :
PRETTY = ${abs_top_srcdir}/script/clang-format.sh
PRETTY_ARGS = -style=file -i
PRETTY_CHECK = ${abs_top_srcdir}/script/clang-format-check.sh
PRETTY_CHECK_ARGS = 
RANLIB = arm-none-eabi-ranlib
SED = /bin/sed
SET_MAKE = 
SHELL = /bin/bash
STRIP = arm-none-eabi-strip
VERSION = 20180926-00440-gbf794ca-dirty
abs_builddir = /home/tri/openthread/build/cc2538/tools/harness-thci
abs_srcdir = /home/tri/openthread/examples/../tools/harness-thci
abs_top_builddir = /home/tri/openthread/build/cc2538
abs_top_nlbuild_autotools_dir = ${abs_top_srcdir}/${nlbuild_autotools_stem}
abs_top_srcdir = /home/tri/openthread/examples/..
ac_ct_AR = 
ac_ct_CC = 
ac_ct_CXX = 
ac_ct_DUMPBIN = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = tar --format=posix -chf - "$$tardir"
am__untar = tar -xf -
bindir = ${exec_prefix}/bin
build = x86_64-unknown-linux-gnu
build_alias = 
build_cpu = x86_64
build_os = linux-gnu
build_vendor = unknown
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = /cc2538
host = arm-none-eabi
host_alias = arm-none-eabi
host_cpu = arm
host_os = eabi
host_vendor = none
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/tri/openthread/third_party/nlbuild-autotools/repo/third_party/autoconf/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
nlbuild_autotools_stem = third_party/nlbuild-autotools/repo
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /
program_transform_name = s,x,x,
psdir = ${docdir}
runstatedir = ${localstatedir}/run
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = /home/tri/openthread/examples/../tools/harness-thci
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../../
top_builddir = ../..
top_srcdir = /home/tri/openthread/examples/..
EXTRA_DIST = \
    OpenThread.py         \
    OpenThread.png        \
    deviceInputFields.xml \
    README.md             \
    $(NULL)

all: all-am

.SUFFIXES:
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign tools/harness-thci/Makefile'; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign tools/harness-thci/Makefile
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

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs
tags TAGS:

ctags CTAGS:

cscope cscopelist:


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
check: check-am
all-am: Makefile
installdirs:
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic clean-libtool mostlyclean-am

distclean: distclean-am
	-rm -f Makefile
distclean-am: clean-am distclean-generic

dvi: dvi-am

dvi-am:

html: html-am

html-am:

info: info-am

info-am:

install-data-am:

install-dvi: install-dvi-am

install-dvi-am:

install-exec-am:

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
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-generic mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am:

.MAKE: install-am install-strip

.PHONY: all all-am check check-am clean clean-generic clean-libtool \
	cscopelist-am ctags-am distclean distclean-generic \
	distclean-libtool distdir dvi dvi-am html html-am info info-am \
	install install-am install-data install-data-am install-dvi \
	install-dvi-am install-exec install-exec-am install-html \
	install-html-am install-info install-info-am install-man \
	install-pdf install-pdf-am install-ps install-ps-am \
	install-strip installcheck installcheck-am installdirs \
	maintainer-clean maintainer-clean-generic mostlyclean \
	mostlyclean-generic mostlyclean-libtool pdf pdf-am ps ps-am \
	tags-am uninstall uninstall-am

.PRECIOUS: Makefile


include $(abs_top_nlbuild_autotools_dir)/automake/pre.am

include $(abs_top_nlbuild_autotools_dir)/automake/post.am

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
