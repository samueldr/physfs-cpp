add_library(physfs++ physfs.cpp)
target_link_libraries(physfs++ physfs)
INSTALL(TARGETS physfs++
		COMPONENT lib
		RUNTIME DESTINATION bin
		LIBRARY DESTINATION lib${LIB_SUFFIX}
		ARCHIVE DESTINATION lib${LIB_SUFFIX})
