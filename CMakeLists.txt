cmake_minimum_required(VERSION 3.20)
project(hw3)

set(CMAKE_CXX_STANDARD 11)

add_executable(hw3 main.cpp Queue.h HealthPoints.cpp HealthPoints.h HealthPointsExampleTest.cpp QueueExampleTests.cpp TestMain.cpp TestUtils.h)
