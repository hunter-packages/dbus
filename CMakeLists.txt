include("cmake/HunterGate.cmake")
HunterGate(
  URL "https://github.com/ruslo/hunter/archive/v0.12.8.tar.gz"
  SHA1 "99b6d48c8e68435ba5095d2598307b762b88b79d"
)


cmake_minimum_required(VERSION 3.2)
project(parent-project)
add_subdirectory(cmake)
