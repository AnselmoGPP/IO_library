CMAKE_MINIMUM_REQUIRED(VERSION 3.12)
PROJECT(iolib)

ADD_EXECUTABLE( ${PROJECT_NAME}
	src/main.cpp
)

TARGET_INCLUDE_DIRECTORIES( ${PROJECT_NAME} PUBLIC
        header
)
