
subdir = src/backend/model
top_builddir = ../../..
include $(top_builddir)/src/Makefile.global
LIBTORCH_DIR = /home/postgres/libtorch
LIBTORCH_INCLUDES = -I$(LIBTORCH_DIR)/include -I$(LIBTORCH_DIR)/include/torch/csrc/api/include


override CPPFLAGS := -I. $(CPPFLAGS) $(LIBTORCH_INCLUDES)

OBJS = libtorch_wrapper.o
	
include $(top_srcdir)/src/backend/common.mk
