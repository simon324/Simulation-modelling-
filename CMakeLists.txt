cmake_minimum_required(VERSION 3.22)
project(Simulation_modelling_)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(Simulation_modelling_
        Helper.cpp
        Helper.hpp
        main.cpp
        Simulation.cpp
        Simulation.hpp)
