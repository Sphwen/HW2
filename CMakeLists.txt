cmake_minimum_required(VERSION 3.6)
project(AnalystComparer)

set(CMAKE_CXX_STANDARD 11)

set(SOURCE_FILES main.cpp Utils.cpp Utils.h Comparer.cpp Comparer.h Constants.h Analyst.h Analyst.cpp History.cpp History.h PurchaseSales.cpp PurchaseSales.h)
add_executable(AnalystComparer ${SOURCE_FILES})