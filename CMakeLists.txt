cmake_minimum_required(VERSION 3.16.3)

# set the project name
project(client)

include_directories(include)

set(SOURCES src/client.c
			)


# add the executable
add_executable(client
			   ${SOURCES})