cmake_minimum_required( VERSION 3.7.1 )

project( jmsd_jitemania_code_base )


JMSD_SHOW_PROJECT_GROUP_HEADER()


set( JMSD_JITEMANIA_EXE_PATH ${PROJECT_SOURCE_DIR}/exe_jm )
set( JMSD_JITEMANIA_LIB_PATH ${PROJECT_SOURCE_DIR}/lib_jm )
set( JMSD_JITEMANIA_TEST_EXE_PATH ${PROJECT_SOURCE_DIR}/test_exe_jm )
set( JMSD_JITEMANIA_TEST_PATH ${PROJECT_SOURCE_DIR}/test_jm )


add_subdirectory( lib_jm )
# add_subdirectory( exe_jm )
# add_subdirectory( test_jm )
# add_subdirectory( test_exe_jm )
# add_subdirectory( xlib_jm )
# add_subdirectory( xexe_jm )



JMSD_SHOW_PROJECT_GROUP_FOOTER()
