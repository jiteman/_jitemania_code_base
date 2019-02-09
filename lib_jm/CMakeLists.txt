cmake_minimum_required( VERSION 3.7.1 )

project( lib_jm )


include( ${JMSD_CMAKE_SETTINGS_PATH}/verbosity/project-group-header.cmake )


add_subdirectory( jmsd_natibase_libs )

# add_subdirectory( jmsd_cppunit_lib )
# add_subdirectory( jmsd_cppunitlite_lib )

# add_subdirectory( jmsd_cule_lib )
# add_subdirectory( jmsd_nutfield_lib )
# add_subdirectory( jmsd_cutflower_lib )


include( ${JMSD_CMAKE_SETTINGS_PATH}/verbosity/project-group-footer.cmake )
