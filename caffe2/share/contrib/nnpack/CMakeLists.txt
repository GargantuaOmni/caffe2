set(Caffe2_CONTRIB_NNPACK_CPU_SRC
  "${CMAKE_CURRENT_SOURCE_DIR}/conv_op.cc"
)
set(Caffe2_CONTRIB_NNPACK_TEST_CPU_SRC
  "${CMAKE_CURRENT_SOURCE_DIR}/conv_op_test.cc"
)

set(Caffe2_CPU_SRCS ${Caffe2_CPU_SRCS} ${Caffe2_CONTRIB_NNPACK_CPU_SRC} PARENT_SCOPE)
set(Caffe2_CPU_TEST_SRCS ${Caffe2_CPU_TEST_SRCS} ${Caffe2_CONTRIB_NNPACK_TEST_CPU_SRC} PARENT_SCOPE)
