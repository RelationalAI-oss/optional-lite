# Copyright 2016 by Martin Moene
#
# https://github.com/martinmoene/optional-lite
#
# This code is licensed under the MIT License (MIT).

if(CMAKE_SOURCE_DIR STREQUAL CMAKE_CURRENT_SOURCE_DIR)

cmake_minimum_required( VERSION 2.8.12 )

	project( optional_lite )

	enable_testing()

	add_subdirectory( test )
	#add_subdirectory( example )
endif()
# end of file
