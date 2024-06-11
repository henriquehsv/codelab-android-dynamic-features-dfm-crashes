cmake_minimum_required(VERSION 3.4.1)

add_library(hello2-jni SHARED
        hello2-jni.c)

# Include libraries needed for hello-jni lib
target_link_libraries(hello2-jni
                      android
                      log)
