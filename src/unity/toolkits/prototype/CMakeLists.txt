project(unity_toolkits)

make_library(unity_prototype
  SOURCES
    sparse_nn.cpp
    class_registrations.cpp
  REQUIRES
    unity_core
)
