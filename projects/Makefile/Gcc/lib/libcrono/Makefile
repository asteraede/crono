########################################################################
# Copyright (c) 1988-2022 $organization$
#
# This software is provided by the author and contributors ``as is''
# and any express or implied warranties, including, but not limited to,
# the implied warranties of merchantability and fitness for a particular
# purpose are disclaimed. In no event shall the author or contributors
# be liable for any direct, indirect, incidental, special, exemplary,
# or consequential damages (including, but not limited to, procurement
# of substitute goods or services; loss of use, data, or profits; or
# business interruption) however caused and on any theory of liability,
# whether in contract, strict liability, or tort (including negligence
# or otherwise) arising in any way out of the use of this software,
# even if advised of the possibility of such damage.
#
#   File: Makefile
#
# Author: $author$
#   Date: 10/14/2022
#
# generic Makefile for framework crono library libcrono
########################################################################
# Depends: rostra;nadir;fila

#
# target
#
libcrono_LIBTARGET = libcrono.${LIBEXT}

########################################################################

#
# user c++ flags
#
libcrono_USRCXXFLAGS += \
${crono_USRCXXFLAGS} \

#
# user defines
#
libcrono_USRDEFINES += \
${crono_USRDEFINES} \
-DDEFAULT_LOGGING_LEVELS_ERROR \
-DXOS_LIB_CRONO_VERSION_BUILD_DATE=10/14/2022 #${shell tdate} \

#
# user includes
#
libcrono_USRINCLUDES += \
${crono_USRINCLUDES} \

#
# user libdirs
#
libcrono_USRLIBDIRS += \
${crono_USRLIBDIRS} \

########################################################################

#
# library .c sources
#
#libcrono_LIB_C_SOURCES += \
#${CRONO_SRC}/xos/lib/crono/version.c \

#
# library .cc sources
#
#libcrono_LIB_CC_SOURCES += \
#${CRONO_SRC}/xos/lib/crono/version.cc \

#
# library .cxx sources
#
#libcrono_LIB_CXX_SOURCES += \
#${CRONO_SRC}/xos/lib/crono/version.cxx \

#
# library .cpp sources
#
libcrono_LIB_CPP_SOURCES += \
${CRONO_SRC}/xos/lib/crono/version.cpp \

#
# library .m sources
#
#libcrono_LIB_M_SOURCES += \
#${CRONO_SRC}/xos/lib/crono/version.m \

#
# library .mm sources
#
#libcrono_LIB_MM_SOURCES += \
#${CRONO_SRC}/xos/lib/crono/version.mm \


########################################################################


