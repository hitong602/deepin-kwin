remove_definitions(-DQT_NO_CAST_FROM_ASCII -DQT_STRICT_ITERATORS -DQT_NO_CAST_FROM_BYTEARRAY -DQT_NO_KEYWORDS)

add_subdirectory( common )
add_subdirectory( kwincompositing )
add_subdirectory( kwinoptions )
add_subdirectory( kwindecoration )
add_subdirectory( kwinrules )
add_subdirectory( kwinscreenedges )
add_subdirectory( kwinscripts )
add_subdirectory( kwindesktop )

if( KWIN_BUILD_TABBOX )
add_subdirectory( kwintabbox )
endif()
