cmake_minimum_required(VERSION 3.20)
project(OCLHeaders)
install(FILES
        CL/cl.h
        CL/cl2.hpp
        CL/cl_d3d10.h
        CL/cl_d3d11.h
        CL/cl_dx9_media_sharing.h
        CL/cl_dx9_media_sharing_intel.h
        CL/cl_egl.h
        CL/cl_ext.h
        CL/cl_ext_intel.h
        CL/cl_gl.h
        CL/cl_gl_ext.h
        CL/cl_half.h
        CL/cl_icd.h
        CL/cl_layer.h
        CL/cl_platform.h
        CL/cl_va_api_media_sharing_intel.h
        CL/cl_version.h
        CL/opencl.h
        CL/opencl.hpp
        DESTINATION ${CMAKE_INSTALL_PREFIX}/include/CL)