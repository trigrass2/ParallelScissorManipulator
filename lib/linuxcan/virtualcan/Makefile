#
# Makefile virtualcan
#

# module name
KV_MODULE_NAME = kvvirtualcan

# Includes
INCLUDES := $(src)/../include/

# source files
SRCS :=           virtualcan.c 
SRCS += ../common/VCanOsIf.c 
SRCS += ../common/objbuf.c 
SRCS += ../common/osif_functions_kernel.c
SRCS += ../common/queue.c

ifneq ($(KERNELRELEASE),)
	RUNDIR := $(src)
else
	RUNDIR := $(PWD)
endif

include $(RUNDIR)/../config.mak
