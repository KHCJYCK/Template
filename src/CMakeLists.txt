include_directories(../include)
aux_source_directory(. src_file) 
 
add_library(srclib ${src_file})   