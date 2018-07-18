rootdir := $(shell pwd)/../../..
project := ubuntu-base

include $(rootdir)/build/common/inc.mk
ifeq ($(hostmaketype), windows)
rootdir := ../../..
endif

####
##  Application targets
####
DEP_HEADERS +=  $(incdir)/libonplatform

apps = libonpeer

kktpeer_SRCS = $(rootdir)/linonpeer/src/main.c
kktpeer_ARCHIVES =
kktpeer_LDLIBS =
kktpeer_DISTSOLIBS =

include $(rootdir)/build/utils/app.mk
