backendlibdir = $(libdir)/backend
backendlib_LTLIBRARIES = libOpenCL-backend.la
libOpenCL_backend_la_SOURCES = \
OclHandler.cpp\
OclHandler.h\
OclHandler_queryPlatformInfo.cpp\
OclHandler_queryDevices.cpp\
OclHandler_contexts.cpp\
OclHandler_memoryObjects.cpp\
OclHandler_commandQueues.cpp\
OclHandler_programObjects.cpp\
OclHandler_kernelObjects.cpp\
OclHandler_executingKernels.cpp\
OclHandler_flushAndFinish.cpp\
OclHandler_eventObjects.cpp\
OclHandler_profilingOperations.cpp

libOpenCL_backend_la_AMCXXFLAGS = -fPIC
libOpenCL_backend_la_LIBADD = $(CUDA_LIB_FLAGS) -lrt -lOpenCL

