cmake_minimum_required(VERSION 3.20)

project(
    SignalForge
    VERSION 0.1.0
    DESCRIPTION "Metadata-driven telemetry decoding framework"
    LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 20)
set(CMAKE_CXX_STANDARD_REQUIRED ON)
set(CMAKE_CXX_EXTENSIONS OFF)

message(STATUS "Building ${PROJECT_NAME} v${PROJECT_VERSION}")